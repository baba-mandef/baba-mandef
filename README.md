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
![Code Time](http://img.shields.io/badge/Code%20Time-805%20hrs%2031%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

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
HTML                     8 hrs 29 mins       █████████████░░░░░░░░░░░░   54.57% 
Python                   3 hrs 45 mins       ██████░░░░░░░░░░░░░░░░░░░   24.09% 
JavaScript               2 hrs 5 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.38% 
Vue.js                   41 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.41% 
CSS                      26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.85%

🔥 Editors: 
VS Code                  15 hrs 34 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      11 hrs 50 mins      ███████████████████░░░░░░   76.0% 
_                        2 hrs 22 mins       ███░░░░░░░░░░░░░░░░░░░░░░   15.25% 
default                  1 hr 21 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.75%

💻 Operating System: 
Linux                    15 hrs 34 mins      █████████████████████████   100.0%

```


 Last Updated on 22/10/2023 18:33:57 UTC
<!--END_SECTION:waka-->
