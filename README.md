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
                           'Telegram': 'ptahemdjehuty',
                           'Mail':'pariso03henri@gmail.com',
                        }
         }
        return Response(ptahemdjehuty, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-739%20hrs%207%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 477 Contributions in the Year 2023
 > 
> 📦 98.5 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 37 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   3 hrs 14 mins       ███████████████████░░░░░░   75.87% 
JavaScript               52 mins             █████░░░░░░░░░░░░░░░░░░░░   20.38% 
Git Config               8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.37% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32% 
Bash                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  4 hrs 16 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   3 hrs 19 mins       ███████████████████░░░░░░   77.64% 
wabo.bj                  53 mins             █████░░░░░░░░░░░░░░░░░░░░   20.7% 
travel-service-api       4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.66%

💻 Operating System: 
Linux                    4 hrs 16 mins       █████████████████████████   100.0%

```


 Last Updated on 17/08/2023 18:34:19 UTC
<!--END_SECTION:waka-->
