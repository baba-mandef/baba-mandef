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
![Code Time](http://img.shields.io/badge/Code%20Time-766%20hrs%2053%20mins-blue)

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
Python                   8 hrs 23 mins       ████████████████░░░░░░░░░   66.88% 
YAML                     1 hr 59 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.83% 
Nginx configuration file 54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.19% 
Nginx Configuration      20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.73% 
XML                      20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.73%

🔥 Editors: 
PyCharmCore              11 hrs 57 mins      ███████████████████████░░   95.3% 
VS Code                  21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.89% 
Android Studio           13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.8%

🐱‍💻 Projects: 
quatro                   6 hrs 50 mins       █████████████░░░░░░░░░░░░   54.5% 
baba-mandef-api          4 hrs 59 mins       ██████████░░░░░░░░░░░░░░░   39.79% 
travel-service-api       29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.9% 
dema                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.8%

💻 Operating System: 
Linux                    12 hrs 33 mins      █████████████████████████   100.0%

```


 Last Updated on 12/09/2023 18:34:07 UTC
<!--END_SECTION:waka-->
