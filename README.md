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
![Code Time](http://img.shields.io/badge/Code%20Time-764%20hrs%2023%20mins-blue)

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
Python                   10 hrs 33 mins      ██████████████████░░░░░░░   74.49% 
YAML                     1 hr 36 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   11.34% 
Nginx configuration file 49 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.79% 
XML                      21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.53% 
Dart                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.38%

🔥 Editors: 
PyCharmCore              13 hrs 21 mins      ███████████████████████░░   94.19% 
Android Studio           28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.32% 
VS Code                  21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.49%

🐱‍💻 Projects: 
quatro                   9 hrs 28 mins       ████████████████░░░░░░░░░   66.83% 
baba-mandef-api          4 hrs 10 mins       ███████░░░░░░░░░░░░░░░░░░   29.38% 
dema                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.41% 
course                   6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.8% 
travel-service-api       3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.46%

💻 Operating System: 
Linux                    14 hrs 10 mins      █████████████████████████   100.0%

```


 Last Updated on 09/09/2023 18:33:51 UTC
<!--END_SECTION:waka-->
