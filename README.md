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
![Code Time](http://img.shields.io/badge/Code%20Time-775%20hrs%2039%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 561 Contributions in the Year 2023
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
Python                   6 hrs 1 min         ██████████████████░░░░░░░   72.39% 
Nginx configuration file 49 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.89% 
YAML                     37 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.52% 
Markdown                 34 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.98% 
JavaScript               7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.52%

🔥 Editors: 
PyCharmCore              5 hrs 54 mins       █████████████████░░░░░░░░   70.94% 
VS Code                  2 hrs 25 mins       ███████░░░░░░░░░░░░░░░░░░   29.06%

🐱‍💻 Projects: 
travel-service-api       5 hrs 40 mins       █████████████████░░░░░░░░   68.21% 
baba-mandef-api          1 hr 27 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.63% 
air-codes                49 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.01% 
quatro                   20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.15%

💻 Operating System: 
Linux                    8 hrs 19 mins       █████████████████████████   100.0%

```


 Last Updated on 21/09/2023 18:34:24 UTC
<!--END_SECTION:waka-->
