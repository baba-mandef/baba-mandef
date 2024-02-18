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
![Code Time](http://img.shields.io/badge/Code%20Time-936%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 87 Contributions in the Year 2024
 > 
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
Python                   16 hrs 48 mins      ████████████████████████░   97.75% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.18% 
Text                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.05% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
VS Code                  17 hrs 11 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
api.ishiro.com           17 hrs 4 mins       ████████████████████████░   99.24% 
api.korbo.fr             7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.76%

💻 Operating System: 
Linux                    17 hrs 11 mins      █████████████████████████   100.0%

```


 Last Updated on 18/02/2024 18:33:27 UTC
<!--END_SECTION:waka-->
