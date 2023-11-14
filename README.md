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
![Code Time](http://img.shields.io/badge/Code%20Time-866%20hrs%2024%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

**🐱 My GitHub Data** 

> 🏆 602 Contributions in the Year 2023
 > 
> 📦 98.7 kB Used in GitHub's Storage 
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
Python                   16 hrs 16 mins      ████████████░░░░░░░░░░░░░   49.77% 
Vue.js                   9 hrs 40 mins       ███████░░░░░░░░░░░░░░░░░░   29.56% 
HTML                     2 hrs 58 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   9.09% 
CSS                      1 hr 19 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.04% 
TypeScript               1 hr 12 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   3.72%

🔥 Editors: 
VS Code                  32 hrs 42 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
korbo.fr                 10 hrs 58 mins      ████████░░░░░░░░░░░░░░░░░   33.53% 
api.korbo.fr             8 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   25.74% 
quatro                   8 hrs 21 mins       ██████░░░░░░░░░░░░░░░░░░░   25.58% 
template_01              4 hrs 55 mins       ███░░░░░░░░░░░░░░░░░░░░░░   15.06% 
sub                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

💻 Operating System: 
Linux                    32 hrs 42 mins      █████████████████████████   100.0%

```


 Last Updated on 14/11/2023 18:33:42 UTC
<!--END_SECTION:waka-->
