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
![Code Time](http://img.shields.io/badge/Code%20Time-684%20hrs%201%20min-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 317 Contributions in the Year 2023
 > 
> 📦 89.2 kB Used in GitHub's Storage 
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
JavaScript               4 hrs 51 mins       ███████████████░░░░░░░░░░   61.81% 
Python                   2 hrs 27 mins       ███████░░░░░░░░░░░░░░░░░░   31.26% 
Bash                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.33% 
Other                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.57% 
TOML                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.53%

🔥 Editors: 
VS Code                  7 hrs 52 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              5 hrs 6 mins        ████████████████░░░░░░░░░   64.83% 
quatro                   2 hrs 9 mins        ███████░░░░░░░░░░░░░░░░░░   27.5% 
baba-mandef-api          36 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.67%

💻 Operating System: 
Linux                    7 hrs 52 mins       █████████████████████████   100.0%

```


 Last Updated on 20/07/2023 05:39:28 UTC
<!--END_SECTION:waka-->
