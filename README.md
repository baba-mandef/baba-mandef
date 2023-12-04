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
![Code Time](http://img.shields.io/badge/Code%20Time-901%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

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
Python                   6 hrs 19 mins       █████████████████░░░░░░░░   67.96% 
HTML                     2 hrs 57 mins       ████████░░░░░░░░░░░░░░░░░   31.75% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  9 hrs 18 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
lavy                     9 hrs 18 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    9 hrs 18 mins       █████████████████████████   100.0%

```


 Last Updated on 04/12/2023 18:35:39 UTC
<!--END_SECTION:waka-->
