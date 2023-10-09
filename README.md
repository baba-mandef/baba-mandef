###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'Name': 'Abiodoun PARAISO',
            'Stack': {
                       'languages': ['Python', 'Php', 'JS', 'Kotlin'],
                       'tools': ['Django', 'DRF', 'NuxtJS', 'React', 'Kotlin', 'Electron'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['freelance web and mobile developer', 'Content creator', 'Teacher', 'Mentor'],
            'AskMe': ['DIY', 'Food', 'Africa', 'Science', 'Comics', 'Photography', 'Tech', 'Programming'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-789%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 580 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 40 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   3 hrs 50 mins       █████████████████████░░░░   86.72% 
Bash                     13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.92% 
GDScript                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.52% 
YAML                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.35% 
Markdown                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.7%

🔥 Editors: 
VS Code                  4 hrs 13 mins       ███████████████████████░░   95.46% 
PyCharmCore              12 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.54%

🐱‍💻 Projects: 
quatro                   3 hrs 9 mins        █████████████████░░░░░░░░   71.09% 
kareeba                  55 mins             █████░░░░░░░░░░░░░░░░░░░░   20.82% 
django-zoho-mail         11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.3% 
iwedioro                 5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.19% 
travel-service-api       4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.6%

💻 Operating System: 
Linux                    4 hrs 25 mins       █████████████████████████   100.0%

```


 Last Updated on 09/10/2023 18:35:30 UTC
<!--END_SECTION:waka-->
