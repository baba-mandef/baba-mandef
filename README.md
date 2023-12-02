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
![Code Time](http://img.shields.io/badge/Code%20Time-900%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

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
Python                   5 hrs 53 mins       █████████████████░░░░░░░░   70.42% 
HTML                     2 hrs 26 mins       ███████░░░░░░░░░░░░░░░░░░   29.26% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  8 hrs 21 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
lavy                     8 hrs 21 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    8 hrs 21 mins       █████████████████████████   100.0%

```


 Last Updated on 02/12/2023 18:33:48 UTC
<!--END_SECTION:waka-->
