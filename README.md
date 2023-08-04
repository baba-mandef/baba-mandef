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
![Code Time](http://img.shields.io/badge/Code%20Time-725%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 447 Contributions in the Year 2023
 > 
> 📦 124.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 44 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   9 hrs               █████████████░░░░░░░░░░░░   54.26% 
JavaScript               6 hrs 49 mins       ██████████░░░░░░░░░░░░░░░   41.12% 
Bash                     41 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.12% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.37% 
TypeScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

🔥 Editors: 
VS Code                  16 hrs 35 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef-api          7 hrs 8 mins        ██████████░░░░░░░░░░░░░░░   43.0% 
baba-mandef              6 hrs 50 mins       ██████████░░░░░░░░░░░░░░░   41.23% 
travel-service-api       2 hrs 36 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.72% 
quatro                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

💻 Operating System: 
Linux                    16 hrs 35 mins      █████████████████████████   100.0%

```


 Last Updated on 04/08/2023 18:33:38 UTC
<!--END_SECTION:waka-->
