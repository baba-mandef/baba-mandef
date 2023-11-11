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
![Code Time](http://img.shields.io/badge/Code%20Time-848%20hrs%202%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

**🐱 My GitHub Data** 

> 🏆 602 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 42 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   16 hrs 21 mins      ███████████████░░░░░░░░░░   61.76% 
Vue.js                   6 hrs 2 mins        █████░░░░░░░░░░░░░░░░░░░░   22.82% 
TypeScript               1 hr 54 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.21% 
HTML                     26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.66% 
JSON                     18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.18%

🔥 Editors: 
VS Code                  26 hrs 29 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   8 hrs 38 mins       ████████░░░░░░░░░░░░░░░░░   32.65% 
korbo.fr                 8 hrs 37 mins       ████████░░░░░░░░░░░░░░░░░   32.57% 
api.korbo.fr             8 hrs 12 mins       ███████░░░░░░░░░░░░░░░░░░   31.01% 
template_01              58 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.68% 
korbo                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

💻 Operating System: 
Linux                    26 hrs 29 mins      █████████████████████████   100.0%

```


 Last Updated on 11/11/2023 18:33:58 UTC
<!--END_SECTION:waka-->
