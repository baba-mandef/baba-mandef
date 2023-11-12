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
![Code Time](http://img.shields.io/badge/Code%20Time-850%20hrs%2051%20mins-blue)

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
Python                   18 hrs 13 mins      ████████████████░░░░░░░░░   64.21% 
Vue.js                   6 hrs 2 mins        █████░░░░░░░░░░░░░░░░░░░░   21.3% 
TypeScript               1 hr 54 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.73% 
HTML                     26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55% 
JSON                     18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.1%

🔥 Editors: 
VS Code                  28 hrs 23 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
api.korbo.fr             9 hrs 49 mins       ████████░░░░░░░░░░░░░░░░░   34.59% 
quatro                   8 hrs 56 mins       ███████░░░░░░░░░░░░░░░░░░   31.49% 
korbo.fr                 8 hrs 37 mins       ███████░░░░░░░░░░░░░░░░░░   30.4% 
template_01              58 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.43% 
korbo                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

💻 Operating System: 
Linux                    28 hrs 23 mins      █████████████████████████   100.0%

```


 Last Updated on 12/11/2023 18:33:43 UTC
<!--END_SECTION:waka-->
