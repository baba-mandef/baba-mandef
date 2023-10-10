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
![Code Time](http://img.shields.io/badge/Code%20Time-789%20hrs%2049%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 580 Contributions in the Year 2023
 > 
> 📦 98.7 kB Used in GitHub's Storage 
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
Python                   3 hrs 29 mins       ███████████████████████░░   93.39% 
GDScript                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.99% 
YAML                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.33% 
TOML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.82% 
Bash                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.46%

🔥 Editors: 
VS Code                  3 hrs 31 mins       ███████████████████████░░   94.62% 
PyCharmCore              12 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.38%

🐱‍💻 Projects: 
quatro                   3 hrs 13 mins       █████████████████████░░░░   86.3% 
kareeba                  19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.6% 
django-zoho-mail         11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.1%

💻 Operating System: 
Linux                    3 hrs 44 mins       █████████████████████████   100.0%

```


 Last Updated on 10/10/2023 18:34:28 UTC
<!--END_SECTION:waka-->
