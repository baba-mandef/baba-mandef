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
![Code Time](http://img.shields.io/badge/Code%20Time-778%20hrs%2013%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 562 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
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
Nginx configuration file 1 hr 8 mins         ███████████░░░░░░░░░░░░░░   44.62% 
Python                   46 mins             ███████░░░░░░░░░░░░░░░░░░   30.09% 
YAML                     37 mins             ██████░░░░░░░░░░░░░░░░░░░   24.31% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52% 
Ezhil                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.35%

🔥 Editors: 
VS Code                  2 hrs 17 mins       ██████████████████████░░░   89.43% 
PyCharmCore              16 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.57%

🐱‍💻 Projects: 
baba-mandef-api          1 hr 46 mins        █████████████████░░░░░░░░   69.41% 
travel-service-api       45 mins             ███████░░░░░░░░░░░░░░░░░░   29.43% 
quatro                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.64% 
baba-mandef              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52%

💻 Operating System: 
Linux                    2 hrs 33 mins       █████████████████████████   100.0%

```


 Last Updated on 27/09/2023 18:35:00 UTC
<!--END_SECTION:waka-->
