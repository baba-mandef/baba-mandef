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
![Code Time](http://img.shields.io/badge/Code%20Time-695%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 363 Contributions in the Year 2023
 > 
> 📦 93.2 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 43 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               8 hrs 39 mins       █████████████░░░░░░░░░░░░   52.52% 
Python                   7 hrs 27 mins       ███████████░░░░░░░░░░░░░░   45.24% 
Bash                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.41% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.75% 
TypeScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  16 hrs 28 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              8 hrs 46 mins       █████████████░░░░░░░░░░░░   53.27% 
baba-mandef-api          3 hrs 57 mins       ██████░░░░░░░░░░░░░░░░░░░   24.03% 
travel-service-api       2 hrs 13 mins       ███░░░░░░░░░░░░░░░░░░░░░░   13.51% 
quatro                   1 hr 30 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.18%

💻 Operating System: 
Linux                    16 hrs 28 mins      █████████████████████████   100.0%

```


 Last Updated on 25/07/2023 18:34:23 UTC
<!--END_SECTION:waka-->
