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
![Code Time](http://img.shields.io/badge/Code%20Time-916%20hrs%2038%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 33 Contributions in the Year 2024
 > 
> 📦 36.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 13 Public Repositories 
 > 
> 🔑 2 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Text                     17 mins             ███████████░░░░░░░░░░░░░░   46.95% 
JavaScript               17 mins             ███████████░░░░░░░░░░░░░░   46.04% 
Python                   2 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   7.02%

🔥 Editors: 
VS Code                  38 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
api.ishiro.com           20 mins             █████████████░░░░░░░░░░░░   53.96% 
abiodoun.dev             17 mins             ███████████░░░░░░░░░░░░░░   46.04%

💻 Operating System: 
Linux                    38 mins             █████████████████████████   100.0%

```


 Last Updated on 07/02/2024 18:33:33 UTC
<!--END_SECTION:waka-->
