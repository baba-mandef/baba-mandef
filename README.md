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
                       'tools': ['Django', 'DRF', 'NuxtJS', 'React', 'Kotlin', 'Electron'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-789%20hrs%2053%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 580 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 40 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   13 mins             ███████████████████░░░░░░   79.16% 
TOML                     1 min               ██░░░░░░░░░░░░░░░░░░░░░░░   10.95% 
Bash                     1 min               █░░░░░░░░░░░░░░░░░░░░░░░░   6.22% 
YAML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.42% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.25%

🔥 Editors: 
VS Code                  16 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   8 mins              █████████████░░░░░░░░░░░░   52.19% 
kareeba                  7 mins              ████████████░░░░░░░░░░░░░   47.81%

💻 Operating System: 
Linux                    16 mins             █████████████████████████   100.0%

```


 Last Updated on 13/10/2023 18:35:45 UTC
<!--END_SECTION:waka-->
