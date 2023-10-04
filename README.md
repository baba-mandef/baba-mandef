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
![Code Time](http://img.shields.io/badge/Code%20Time-786%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 580 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 40 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   8 hrs 48 mins       ██████████████████████░░░   90.88% 
Text                     33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.82% 
Bash                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.07% 
Markdown                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77% 
Other                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.25%

🔥 Editors: 
VS Code                  9 hrs 42 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
iwedioro                 7 hrs 16 mins       ██████████████████░░░░░░░   74.92% 
quatro                   1 hr 45 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.15% 
kareeba                  36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.2% 
travel-service-api       4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.73%

💻 Operating System: 
Linux                    9 hrs 42 mins       █████████████████████████   100.0%

```


 Last Updated on 04/10/2023 18:36:15 UTC
<!--END_SECTION:waka-->
