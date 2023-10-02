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
![Code Time](http://img.shields.io/badge/Code%20Time-781%20hrs%2016%20mins-blue)

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
Python                   6 hrs 47 mins       ███████████████████████░░   92.58% 
Text                     32 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.42%

🔥 Editors: 
VS Code                  7 hrs 10 mins       ████████████████████████░   97.86% 
PyCharmCore              9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.14%

🐱‍💻 Projects: 
iwedioro                 7 hrs 10 mins       ████████████████████████░   97.86% 
travel-service-api       8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.92% 
quatro                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.22%

💻 Operating System: 
Linux                    7 hrs 19 mins       █████████████████████████   100.0%

```


 Last Updated on 02/10/2023 18:35:44 UTC
<!--END_SECTION:waka-->
