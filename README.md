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
![Code Time](http://img.shields.io/badge/Code%20Time-766%20hrs%202%20mins-blue)

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
Python                   10 hrs 9 mins       █████████████████░░░░░░░░   69.75% 
YAML                     1 hr 59 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.66% 
Nginx configuration file 54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.2% 
XML                      26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.07% 
Nginx Configuration      20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.36%

🔥 Editors: 
PyCharmCore              13 hrs 43 mins      ███████████████████████░░   94.27% 
Android Studio           28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.24% 
VS Code                  21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.5%

🐱‍💻 Projects: 
quatro                   9 hrs 1 min         ███████████████░░░░░░░░░░   62.0% 
baba-mandef-api          4 hrs 59 mins       ████████░░░░░░░░░░░░░░░░░   34.32% 
dema                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.35% 
course                   6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.78% 
travel-service-api       3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.45%

💻 Operating System: 
Linux                    14 hrs 33 mins      █████████████████████████   100.0%

```


 Last Updated on 10/09/2023 18:33:54 UTC
<!--END_SECTION:waka-->
