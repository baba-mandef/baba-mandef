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
![Code Time](http://img.shields.io/badge/Code%20Time-712%20hrs%2030%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 414 Contributions in the Year 2023
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
Python                   12 hrs 17 mins      ███████████████░░░░░░░░░░   59.52% 
JavaScript               7 hrs 43 mins       █████████░░░░░░░░░░░░░░░░   37.4% 
Bash                     26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.16% 
JSON                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.46% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3%

🔥 Editors: 
VS Code                  20 hrs 39 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              7 hrs 44 mins       █████████░░░░░░░░░░░░░░░░   37.47% 
baba-mandef-api          6 hrs 40 mins       ████████░░░░░░░░░░░░░░░░░   32.28% 
travel-service-api       5 hrs 10 mins       ██████░░░░░░░░░░░░░░░░░░░   25.05% 
followtrainbot           57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.62% 
planetech_market         5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44%

💻 Operating System: 
Linux                    20 hrs 39 mins      █████████████████████████   100.0%

```


 Last Updated on 31/07/2023 18:34:09 UTC
<!--END_SECTION:waka-->
