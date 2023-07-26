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
![Code Time](http://img.shields.io/badge/Code%20Time-698%20hrs%2059%20mins-blue)

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
JavaScript               10 hrs 48 mins      ██████████████░░░░░░░░░░░   56.84% 
Python                   7 hrs 54 mins       ██████████░░░░░░░░░░░░░░░   41.55% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.11% 
Bash                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.29% 
XML                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

🔥 Editors: 
VS Code                  19 hrs              █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              10 hrs 57 mins      ██████████████░░░░░░░░░░░   57.64% 
baba-mandef-api          3 hrs 57 mins       █████░░░░░░░░░░░░░░░░░░░░   20.83% 
travel-service-api       3 hrs 2 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.03% 
followtrainbot           57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.02% 
planetech_market         5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.48%

💻 Operating System: 
Linux                    19 hrs              █████████████████████████   100.0%

```


 Last Updated on 26/07/2023 18:34:16 UTC
<!--END_SECTION:waka-->
