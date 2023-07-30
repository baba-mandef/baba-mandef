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
![Code Time](http://img.shields.io/badge/Code%20Time-712%20hrs%2013%20mins-blue)

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
Python                   9 hrs 25 mins       ██████████████░░░░░░░░░░░   55.59% 
JavaScript               7 hrs 12 mins       ██████████░░░░░░░░░░░░░░░   42.51% 
Bash                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.92% 
JSON                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21%

🔥 Editors: 
VS Code                  16 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              7 hrs 13 mins       ██████████░░░░░░░░░░░░░░░   42.59% 
travel-service-api       5 hrs 10 mins       ███████░░░░░░░░░░░░░░░░░░   30.51% 
baba-mandef-api          3 hrs 29 mins       █████░░░░░░░░░░░░░░░░░░░░   20.56% 
followtrainbot           57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.63% 
planetech_market         5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.54%

💻 Operating System: 
Linux                    16 hrs 57 mins      █████████████████████████   100.0%

```


 Last Updated on 30/07/2023 18:34:02 UTC
<!--END_SECTION:waka-->
