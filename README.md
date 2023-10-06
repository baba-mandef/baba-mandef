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
![Code Time](http://img.shields.io/badge/Code%20Time-788%20hrs%2042%20mins-blue)

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
Python                   9 hrs 52 mins       ███████████████████████░░   94.9% 
Bash                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.93% 
GDScript                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.07% 
YAML                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.91% 
Markdown                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.72%

🔥 Editors: 
VS Code                  10 hrs 11 mins      ████████████████████████░   98.07% 
PyCharmCore              12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.93%

🐱‍💻 Projects: 
iwedioro                 6 hrs 16 mins       ███████████████░░░░░░░░░░   60.3% 
quatro                   3 hrs 4 mins        ███████░░░░░░░░░░░░░░░░░░   29.59% 
kareeba                  47 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.59% 
django-zoho-mail         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.83% 
travel-service-api       4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.68%

💻 Operating System: 
Linux                    10 hrs 23 mins      █████████████████████████   100.0%

```


 Last Updated on 06/10/2023 18:35:19 UTC
<!--END_SECTION:waka-->
