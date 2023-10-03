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
![Code Time](http://img.shields.io/badge/Code%20Time-785%20hrs%2023%20mins-blue)

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
Python                   7 hrs 3 mins        ██████████████████████░░░   88.85% 
Text                     33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.11% 
Bash                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.53% 
Markdown                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.95% 
Other                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.31%

🔥 Editors: 
VS Code                  7 hrs 56 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
iwedioro                 7 hrs 16 mins       ███████████████████████░░   91.53% 
kareeba                  36 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.58% 
travel-service-api       4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89%

💻 Operating System: 
Linux                    7 hrs 56 mins       █████████████████████████   100.0%

```


 Last Updated on 03/10/2023 18:35:39 UTC
<!--END_SECTION:waka-->
