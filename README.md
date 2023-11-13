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
![Code Time](http://img.shields.io/badge/Code%20Time-857%20hrs%2046%20mins-blue)

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
Python                   16 hrs 14 mins      █████████████░░░░░░░░░░░░   52.65% 
Vue.js                   10 hrs 16 mins      ████████░░░░░░░░░░░░░░░░░   33.33% 
TypeScript               2 hrs 21 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   7.64% 
HTML                     26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.43% 
JSON                     17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94%

🔥 Editors: 
VS Code                  30 hrs 50 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
korbo.fr                 13 hrs 7 mins       ██████████░░░░░░░░░░░░░░░   42.53% 
api.korbo.fr             8 hrs 22 mins       ██████░░░░░░░░░░░░░░░░░░░   27.17% 
quatro                   8 hrs 21 mins       ██████░░░░░░░░░░░░░░░░░░░   27.12% 
template_01              58 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.16% 
Modernize-nuxtjs-free    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    30 hrs 50 mins      █████████████████████████   100.0%

```


 Last Updated on 13/11/2023 05:31:30 UTC
<!--END_SECTION:waka-->
