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
![Code Time](http://img.shields.io/badge/Code%20Time-772%20hrs%2048%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 540 Contributions in the Year 2023
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
Python                   7 hrs 53 mins       ████████████████████░░░░░   82.94% 
Markdown                 34 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.1% 
YAML                     22 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.02% 
Nginx Configuration      12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.28% 
JavaScript               7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.33%

🔥 Editors: 
PyCharmCore              8 hrs 33 mins       ██████████████████████░░░   89.9% 
VS Code                  57 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.1%

🐱‍💻 Projects: 
travel-service-api       6 hrs 47 mins       █████████████████░░░░░░░░   71.33% 
quatro                   1 hr 3 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   11.15% 
baba-mandef-api          50 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.77% 
air-codes                49 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.75%

💻 Operating System: 
Linux                    9 hrs 30 mins       █████████████████████████   100.0%

```


 Last Updated on 16/09/2023 18:33:45 UTC
<!--END_SECTION:waka-->
