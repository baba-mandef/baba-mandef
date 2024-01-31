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
![Code Time](http://img.shields.io/badge/Code%20Time-909%20hrs%204%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 29 Contributions in the Year 2024
 > 
> 📦 36.5 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 12 Public Repositories 
 > 
> 🔑 2 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               11 hrs 58 mins      ███████████████████████░░   92.49% 
Python                   27 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.59% 
Markdown                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.39% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.06% 
Other                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.0%

🔥 Editors: 
VS Code                  12 hrs 56 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
abiodoun.dev             12 hrs 1 min        ███████████████████████░░   92.93% 
investing_telegram_bot   23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.99% 
Unknown Project          20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.61% 
api.abiodoun.dev         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.47%

💻 Operating System: 
Linux                    12 hrs 56 mins      █████████████████████████   100.0%

```


 Last Updated on 31/01/2024 18:33:19 UTC
<!--END_SECTION:waka-->
