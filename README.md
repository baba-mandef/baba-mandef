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
![Code Time](http://img.shields.io/badge/Code%20Time-706%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 370 Contributions in the Year 2023
 > 
> 📦 106.5 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 45 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   9 hrs 25 mins       █████████████░░░░░░░░░░░░   51.55% 
JavaScript               8 hrs 39 mins       ███████████░░░░░░░░░░░░░░   47.39% 
JSON                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.51% 
Bash                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3% 
XML                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

🔥 Editors: 
VS Code                  18 hrs 16 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              8 hrs 41 mins       ████████████░░░░░░░░░░░░░   47.5% 
travel-service-api       5 hrs 10 mins       ███████░░░░░░░░░░░░░░░░░░   28.31% 
baba-mandef-api          3 hrs 21 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.36% 
followtrainbot           57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.22% 
planetech_market         5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5%

💻 Operating System: 
Linux                    18 hrs 16 mins      █████████████████████████   100.0%

```


 Last Updated on 28/07/2023 18:33:58 UTC
<!--END_SECTION:waka-->
