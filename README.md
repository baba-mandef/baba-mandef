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
![Code Time](http://img.shields.io/badge/Code%20Time-689%20hrs%2022%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 337 Contributions in the Year 2023
 > 
> 📦 89.3 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 40 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               5 hrs 24 mins       ████████████████░░░░░░░░░   64.27% 
Python                   2 hrs 27 mins       ███████░░░░░░░░░░░░░░░░░░   29.24% 
Bash                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.18% 
Other                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.47% 
TOML                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.43%

🔥 Editors: 
VS Code                  8 hrs 24 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              5 hrs 38 mins       ████████████████░░░░░░░░░   67.1% 
quatro                   2 hrs 9 mins        ██████░░░░░░░░░░░░░░░░░░░   25.72% 
baba-mandef-api          36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.18%

💻 Operating System: 
Linux                    8 hrs 24 mins       █████████████████████████   100.0%

```


 Last Updated on 21/07/2023 18:35:17 UTC
<!--END_SECTION:waka-->
