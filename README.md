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
![Code Time](http://img.shields.io/badge/Code%20Time-846%20hrs%2041%20mins-blue)

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
Python                   19 hrs 56 mins      █████████████████░░░░░░░░   68.54% 
Vue.js                   6 hrs 2 mins        █████░░░░░░░░░░░░░░░░░░░░   20.77% 
TypeScript               1 hr 54 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.56% 
Text                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.92% 
JSON                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.79%

🔥 Editors: 
VS Code                  29 hrs 6 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   11 hrs 2 mins       █████████░░░░░░░░░░░░░░░░   37.96% 
api.korbo.fr             9 hrs 24 mins       ████████░░░░░░░░░░░░░░░░░   32.31% 
korbo.fr                 8 hrs 37 mins       ███████░░░░░░░░░░░░░░░░░░   29.65% 
korbo                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08% 
Modernize-nuxtjs-free    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    29 hrs 6 mins       █████████████████████████   100.0%

```


 Last Updated on 10/11/2023 18:34:30 UTC
<!--END_SECTION:waka-->
