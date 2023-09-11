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
Python                   9 hrs 29 mins       █████████████████░░░░░░░░   68.3% 
YAML                     1 hr 59 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.31% 
Nginx configuration file 54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.5% 
XML                      26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.22% 
Nginx Configuration      20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.47%

🔥 Editors: 
PyCharmCore              13 hrs 3 mins       ███████████████████████░░   93.99% 
Android Studio           28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.39% 
VS Code                  21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.62%

🐱‍💻 Projects: 
quatro                   8 hrs 21 mins       ███████████████░░░░░░░░░░   60.16% 
baba-mandef-api          4 hrs 59 mins       █████████░░░░░░░░░░░░░░░░   35.97% 
dema                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.46% 
course                   6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81% 
travel-service-api       3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.47%

💻 Operating System: 
Linux                    13 hrs 53 mins      █████████████████████████   100.0%

```


 Last Updated on 11/09/2023 18:34:19 UTC
<!--END_SECTION:waka-->
