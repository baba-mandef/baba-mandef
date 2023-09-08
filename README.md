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
![Code Time](http://img.shields.io/badge/Code%20Time-762%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 527 Contributions in the Year 2023
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
Python                   10 hrs 2 mins       ███████████████████░░░░░░   78.85% 
YAML                     52 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.88% 
Nginx configuration file 45 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.9% 
XML                      19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.57% 
Dart                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.54%

🔥 Editors: 
PyCharmCore              12 hrs 3 mins       ███████████████████████░░   94.59% 
Android Studio           29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.88% 
VS Code                  11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.53%

🐱‍💻 Projects: 
quatro                   9 hrs 22 mins       ██████████████████░░░░░░░   73.6% 
baba-mandef-api          2 hrs 48 mins       █████░░░░░░░░░░░░░░░░░░░░   22.0% 
dema                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.68% 
course                   8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.06% 
travel-service-api       3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52%

💻 Operating System: 
Linux                    12 hrs 44 mins      █████████████████████████   100.0%

```


 Last Updated on 08/09/2023 18:34:08 UTC
<!--END_SECTION:waka-->
