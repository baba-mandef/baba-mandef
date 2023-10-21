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
![Code Time](http://img.shields.io/badge/Code%20Time-800%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 581 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 41 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     8 hrs 29 mins       █████████████░░░░░░░░░░░░   54.37% 
Python                   3 hrs 45 mins       ██████░░░░░░░░░░░░░░░░░░░   24.01% 
JavaScript               2 hrs 5 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.33% 
Vue.js                   44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.76% 
CSS                      26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.84%

🔥 Editors: 
VS Code                  15 hrs 37 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      11 hrs 50 mins      ███████████████████░░░░░░   75.73% 
_                        2 hrs 25 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.55% 
default                  1 hr 21 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.72%

💻 Operating System: 
Linux                    15 hrs 37 mins      █████████████████████████   100.0%

```


 Last Updated on 21/10/2023 18:33:34 UTC
<!--END_SECTION:waka-->
