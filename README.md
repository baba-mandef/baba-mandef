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
![Code Time](http://img.shields.io/badge/Code%20Time-875%20hrs%2029%20mins-blue)

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
HTML                     12 hrs 53 mins      ██████████░░░░░░░░░░░░░░░   43.24% 
Vue.js                   8 hrs 47 mins       ███████░░░░░░░░░░░░░░░░░░   29.47% 
Python                   5 hrs 24 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.13% 
CSS                      1 hr 24 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.72% 
TypeScript               42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.36%

🔥 Editors: 
VS Code                  29 hrs 49 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
template_01              13 hrs 23 mins      ███████████░░░░░░░░░░░░░░   44.9% 
korbo.fr                 9 hrs 30 mins       ████████░░░░░░░░░░░░░░░░░   31.86% 
api.korbo.fr             4 hrs 28 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.99% 
sub                      2 hrs 2 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.83% 
quatro                   25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.42%

💻 Operating System: 
Linux                    29 hrs 49 mins      █████████████████████████   100.0%

```


 Last Updated on 18/11/2023 18:33:26 UTC
<!--END_SECTION:waka-->
