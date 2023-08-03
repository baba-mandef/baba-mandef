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
![Code Time](http://img.shields.io/badge/Code%20Time-721%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 433 Contributions in the Year 2023
 > 
> 📦 106.6 kB Used in GitHub's Storage 
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
JavaScript               9 hrs 11 mins       ████████████░░░░░░░░░░░░░   48.47% 
Python                   9 hrs               ███████████░░░░░░░░░░░░░░   47.49% 
Bash                     41 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.61% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32% 
TypeScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

🔥 Editors: 
VS Code                  18 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              9 hrs 12 mins       ████████████░░░░░░░░░░░░░   48.57% 
baba-mandef-api          7 hrs 8 mins        █████████░░░░░░░░░░░░░░░░   37.64% 
travel-service-api       2 hrs 36 mins       ███░░░░░░░░░░░░░░░░░░░░░░   13.76% 
quatro                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

💻 Operating System: 
Linux                    18 hrs 57 mins      █████████████████████████   100.0%

```


 Last Updated on 03/08/2023 18:33:39 UTC
<!--END_SECTION:waka-->
