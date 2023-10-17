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
![Code Time](http://img.shields.io/badge/Code%20Time-789%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 580 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 40 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     2 hrs 28 mins       █████████░░░░░░░░░░░░░░░░   38.26% 
JavaScript               1 hr 59 mins        ███████░░░░░░░░░░░░░░░░░░   30.85% 
Python                   1 hr 5 mins         ████░░░░░░░░░░░░░░░░░░░░░   16.83% 
Vue.js                   44 mins             ███░░░░░░░░░░░░░░░░░░░░░░   11.5% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.6%

🔥 Editors: 
VS Code                  6 hrs 27 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      3 hrs 3 mins        ███████████░░░░░░░░░░░░░░   47.25% 
_                        2 hrs 25 mins       █████████░░░░░░░░░░░░░░░░   37.61% 
default                  58 mins             ███░░░░░░░░░░░░░░░░░░░░░░   15.14%

💻 Operating System: 
Linux                    6 hrs 27 mins       █████████████████████████   100.0%

```


 Last Updated on 17/10/2023 18:36:30 UTC
<!--END_SECTION:waka-->
