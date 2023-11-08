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
![Code Time](http://img.shields.io/badge/Code%20Time-836%20hrs%2050%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

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
Python                   18 hrs 16 mins      ████████████████░░░░░░░░░   67.32% 
Vue.js                   5 hrs 59 mins       █████░░░░░░░░░░░░░░░░░░░░   22.06% 
TypeScript               1 hr 54 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.03% 
JSON                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.85% 
Other                    12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.76%

🔥 Editors: 
VS Code                  27 hrs 8 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
api.korbo.fr             9 hrs 36 mins       ████████░░░░░░░░░░░░░░░░░   35.37% 
quatro                   8 hrs 56 mins       ████████░░░░░░░░░░░░░░░░░   32.95% 
korbo.fr                 8 hrs 34 mins       ████████░░░░░░░░░░░░░░░░░   31.57% 
korbo                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08% 
Modernize-nuxtjs-free    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    27 hrs 8 mins       █████████████████████████   100.0%

```


 Last Updated on 08/11/2023 18:34:41 UTC
<!--END_SECTION:waka-->
