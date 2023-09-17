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
![Code Time](http://img.shields.io/badge/Code%20Time-775%20hrs%2033%20mins-blue)

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
Python                   7 hrs 50 mins       ██████████████████████░░░   90.34% 
Markdown                 34 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.69% 
JavaScript               7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.46% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.43% 
YAML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
PyCharmCore              7 hrs 43 mins       ██████████████████████░░░   89.04% 
VS Code                  57 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.96%

🐱‍💻 Projects: 
travel-service-api       6 hrs 47 mins       ███████████████████░░░░░░   78.22% 
quatro                   1 hr 3 mins         ███░░░░░░░░░░░░░░░░░░░░░░   12.11% 
air-codes                49 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.59% 
baba-mandef-api          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07%

💻 Operating System: 
Linux                    8 hrs 40 mins       █████████████████████████   100.0%

```


 Last Updated on 17/09/2023 18:34:07 UTC
<!--END_SECTION:waka-->
