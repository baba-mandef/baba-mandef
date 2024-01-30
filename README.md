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
![Code Time](http://img.shields.io/badge/Code%20Time-908%20hrs%2031%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 23 Contributions in the Year 2024
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
JavaScript               5 hrs 15 mins       ██████████████████████░░░   87.5% 
Python                   24 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.92% 
Markdown                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.99% 
Other                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.15% 
JSON                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

🔥 Editors: 
VS Code                  6 hrs               █████████████████████████   100.0%

🐱‍💻 Projects: 
abiodoun.dev             5 hrs 17 mins       ██████████████████████░░░   87.94% 
investing_telegram_bot   23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.44% 
Unknown Project          20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.62%

💻 Operating System: 
Linux                    6 hrs               █████████████████████████   100.0%

```


 Last Updated on 30/01/2024 18:33:16 UTC
<!--END_SECTION:waka-->
