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
![Code Time](http://img.shields.io/badge/Code%20Time-789%20hrs%2036%20mins-blue)

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
Python                   8 hrs 55 mins       ███████████████████████░░   94.39% 
Bash                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.12% 
GDScript                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.18% 
YAML                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.0% 
Markdown                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.8%

🔥 Editors: 
VS Code                  9 hrs 14 mins       ████████████████████████░   97.87% 
PyCharmCore              12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.13%

🐱‍💻 Projects: 
iwedioro                 5 hrs 19 mins       ██████████████░░░░░░░░░░░   56.31% 
quatro                   3 hrs 4 mins        ████████░░░░░░░░░░░░░░░░░   32.57% 
kareeba                  47 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.36% 
django-zoho-mail         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.02% 
travel-service-api       4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.75%

💻 Operating System: 
Linux                    9 hrs 26 mins       █████████████████████████   100.0%

```


 Last Updated on 07/10/2023 18:34:07 UTC
<!--END_SECTION:waka-->
