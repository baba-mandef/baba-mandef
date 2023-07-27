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
![Code Time](http://img.shields.io/badge/Code%20Time-703%20hrs%202%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 364 Contributions in the Year 2023
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
Python                   9 hrs 25 mins       ██████████████░░░░░░░░░░░   57.26% 
JavaScript               6 hrs 50 mins       ██████████░░░░░░░░░░░░░░░   41.56% 
JSON                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57% 
Bash                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.33% 
XML                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

🔥 Editors: 
VS Code                  16 hrs 27 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              6 hrs 51 mins       ██████████░░░░░░░░░░░░░░░   41.69% 
travel-service-api       5 hrs 10 mins       ███████░░░░░░░░░░░░░░░░░░   31.45% 
baba-mandef-api          3 hrs 21 mins       █████░░░░░░░░░░░░░░░░░░░░   20.39% 
followtrainbot           57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.8% 
planetech_market         5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56%

💻 Operating System: 
Linux                    16 hrs 27 mins      █████████████████████████   100.0%

```


 Last Updated on 27/07/2023 18:33:53 UTC
<!--END_SECTION:waka-->
