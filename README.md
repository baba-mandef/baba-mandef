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
![Code Time](http://img.shields.io/badge/Code%20Time-796%20hrs%2021%20mins-blue)

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
HTML                     3 hrs 10 mins       ███████████░░░░░░░░░░░░░░   43.87% 
JavaScript               1 hr 59 mins        ███████░░░░░░░░░░░░░░░░░░   27.59% 
Python                   1 hr 9 mins         ████░░░░░░░░░░░░░░░░░░░░░   15.97% 
Vue.js                   44 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.29% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.43%

🔥 Editors: 
VS Code                  7 hrs 13 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      3 hrs 49 mins       █████████████░░░░░░░░░░░░   52.83% 
_                        2 hrs 25 mins       ████████░░░░░░░░░░░░░░░░░   33.63% 
default                  58 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.54%

💻 Operating System: 
Linux                    7 hrs 13 mins       █████████████████████████   100.0%

```


 Last Updated on 18/10/2023 18:36:28 UTC
<!--END_SECTION:waka-->
