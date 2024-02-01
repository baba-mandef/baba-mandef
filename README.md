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
![Code Time](http://img.shields.io/badge/Code%20Time-916%20hrs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 32 Contributions in the Year 2024
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
JavaScript               12 hrs 16 mins      ███████████████████████░░   92.66% 
Python                   27 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.51% 
Markdown                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.36% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.03% 
Other                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.98%

🔥 Editors: 
VS Code                  13 hrs 14 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
abiodoun.dev             12 hrs 19 mins      ███████████████████████░░   93.09% 
investing_telegram_bot   23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.92% 
Unknown Project          20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.55% 
api.abiodoun.dev         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.44%

💻 Operating System: 
Linux                    13 hrs 14 mins      █████████████████████████   100.0%

```


 Last Updated on 01/02/2024 18:34:22 UTC
<!--END_SECTION:waka-->
