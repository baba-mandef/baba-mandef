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
JavaScript               7 hrs               ███████████████████████░░   92.55% 
Text                     26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.74% 
Python                   5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.24% 
TypeScript               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.41% 
Docker                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

🔥 Editors: 
VS Code                  7 hrs 34 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
abiodoun.dev             7 hrs 2 mins        ███████████████████████░░   92.96% 
api.ishiro.com           20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.53% 
api.abiodoun.dev         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.51%

💻 Operating System: 
Linux                    7 hrs 34 mins       █████████████████████████   100.0%

```


 Last Updated on 06/02/2024 18:33:31 UTC
<!--END_SECTION:waka-->
