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
![Code Time](http://img.shields.io/badge/Code%20Time-708%20hrs%2027%20mins-blue)

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
Python                   9 hrs 33 mins       ██████████████░░░░░░░░░░░   57.06% 
JavaScript               6 hrs 57 mins       ██████████░░░░░░░░░░░░░░░   41.51% 
JSON                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56% 
Bash                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.45% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.22%

🔥 Editors: 
VS Code                  16 hrs 45 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              6 hrs 58 mins       ██████████░░░░░░░░░░░░░░░   41.59% 
travel-service-api       5 hrs 10 mins       ███████░░░░░░░░░░░░░░░░░░   30.9% 
baba-mandef-api          3 hrs 32 mins       █████░░░░░░░░░░░░░░░░░░░░   21.11% 
followtrainbot           57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.7% 
planetech_market         5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.55%

💻 Operating System: 
Linux                    16 hrs 45 mins      █████████████████████████   100.0%

```


 Last Updated on 29/07/2023 18:34:14 UTC
<!--END_SECTION:waka-->
