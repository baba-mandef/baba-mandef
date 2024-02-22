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
                       'tools': ['Django', 'VueJS', 'React', 'Jetpack Compose'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-943%20hrs%206%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 📦 36.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 14 Public Repositories 
 > 
> 🔑 2 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   11 hrs 24 mins      ████████████████████████░   98.1% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.74% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  11 hrs 37 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
api.ishiro.com           11 hrs 37 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    11 hrs 37 mins      █████████████████████████   100.0%

```


 Last Updated on 22/02/2024 18:33:48 UTC
<!--END_SECTION:waka-->
