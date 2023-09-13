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
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-767%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 533 Contributions in the Year 2023
 > 
> 📦 98.5 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 38 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   5 hrs 50 mins       ███████████████░░░░░░░░░░   59.73% 
YAML                     1 hr 59 mins        █████░░░░░░░░░░░░░░░░░░░░   20.37% 
Nginx configuration file 54 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.23% 
Nginx Configuration      20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.51% 
XML                      18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.1%

🔥 Editors: 
PyCharmCore              9 hrs 24 mins       ████████████████████████░   96.28% 
VS Code                  21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.72%

🐱‍💻 Projects: 
baba-mandef-api          4 hrs 59 mins       ████████████░░░░░░░░░░░░░   51.16% 
quatro                   4 hrs 16 mins       ███████████░░░░░░░░░░░░░░   43.81% 
travel-service-api       29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.03%

💻 Operating System: 
Linux                    9 hrs 46 mins       █████████████████████████   100.0%

```


 Last Updated on 13/09/2023 18:34:36 UTC
<!--END_SECTION:waka-->
