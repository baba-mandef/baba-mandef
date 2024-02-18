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
![Code Time](http://img.shields.io/badge/Code%20Time-934%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 86 Contributions in the Year 2024
 > 
> 📦 36.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 14 Public Repositories 
 > 
> 🔑 2 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    149 commits    ███████░░░░░░░░░░░░░░░░░░   29.33% 
🌆 Daytime    223 commits    ███████████░░░░░░░░░░░░░░   43.9% 
🌃 Evening    94 commits     ████░░░░░░░░░░░░░░░░░░░░░   18.5% 
🌙 Night      42 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.27%

```


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


 Last Updated on 18/02/2024 08:31:15 UTC
<!--END_SECTION:waka-->
