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
![Code Time](http://img.shields.io/badge/Code%20Time-738%20hrs%2021%20mins-blue)

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
JavaScript               4 hrs 9 mins        ███████████████████░░░░░░   79.29% 
Python                   45 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.31% 
CSS                      15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.79% 
HTML                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.48% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  5 hrs 14 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
wabo.bj                  4 hrs 29 mins       █████████████████████░░░░   85.69% 
quatro                   40 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.96% 
travel-service-api       4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.35%

💻 Operating System: 
Linux                    5 hrs 14 mins       █████████████████████████   100.0%

```


 Last Updated on 15/08/2023 18:33:49 UTC
<!--END_SECTION:waka-->
