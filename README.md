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
![Code Time](http://img.shields.io/badge/Code%20Time-903%20hrs%2023%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 3 Contributions in the Year 2024
 > 
> 📦 36.8 kB Used in GitHub's Storage 
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
Python                   12 mins             ███████████████░░░░░░░░░░   61.66% 
Other                    7 mins              █████████░░░░░░░░░░░░░░░░   38.34%

🔥 Editors: 
VS Code                  20 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
Unknown Project          20 mins             █████████████████████████   100.0%

💻 Operating System: 
Linux                    20 mins             █████████████████████████   100.0%

```


 Last Updated on 28/01/2024 18:33:29 UTC
<!--END_SECTION:waka-->
