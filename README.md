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

> 🏆 549 Contributions in the Year 2023
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
Python                   6 hrs 45 mins       ██████████████████████░░░   88.56% 
Markdown                 34 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.6% 
JavaScript               7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.66% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.62% 
YAML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26%

🔥 Editors: 
PyCharmCore              6 hrs 38 mins       █████████████████████░░░░   87.03% 
VS Code                  59 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.97%

🐱‍💻 Projects: 
travel-service-api       6 hrs 24 mins       █████████████████████░░░░   83.98% 
air-codes                49 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.89% 
quatro                   20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.57% 
baba-mandef-api          2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56%

💻 Operating System: 
Linux                    7 hrs 38 mins       █████████████████████████   100.0%

```


 Last Updated on 20/09/2023 18:34:57 UTC
<!--END_SECTION:waka-->
