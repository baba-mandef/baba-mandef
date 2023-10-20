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
![Code Time](http://img.shields.io/badge/Code%20Time-799%20hrs%203%20mins-blue)

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
HTML                     5 hrs 34 mins       █████████████░░░░░░░░░░░░   54.6% 
JavaScript               2 hrs 4 mins        █████░░░░░░░░░░░░░░░░░░░░   20.43% 
Python                   1 hr 16 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.51% 
Vue.js                   44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.29% 
CSS                      25 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.09%

🔥 Editors: 
VS Code                  10 hrs 11 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      6 hrs 35 mins       ████████████████░░░░░░░░░   64.71% 
_                        2 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   23.84% 
default                  1 hr 10 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   11.45%

💻 Operating System: 
Linux                    10 hrs 11 mins      █████████████████████████   100.0%

```


 Last Updated on 20/10/2023 18:34:19 UTC
<!--END_SECTION:waka-->
