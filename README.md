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
![Code Time](http://img.shields.io/badge/Code%20Time-932%20hrs%2040%20mins-blue)

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
Python                   14 hrs 43 mins      ████████████████████████░   97.45% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.34% 
Text                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.2% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
VS Code                  15 hrs 6 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
api.ishiro.com           14 hrs 58 mins      ████████████████████████░   99.14% 
api.korbo.fr             7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.86%

💻 Operating System: 
Linux                    15 hrs 6 mins       █████████████████████████   100.0%

```


 Last Updated on 17/02/2024 18:33:27 UTC
<!--END_SECTION:waka-->
