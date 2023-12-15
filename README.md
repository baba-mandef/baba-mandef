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
![Code Time](http://img.shields.io/badge/Code%20Time-902%20hrs%202%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 602 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 42 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   16 mins             █████████████░░░░░░░░░░░░   52.33% 
Text                     7 mins              ██████░░░░░░░░░░░░░░░░░░░   25.0% 
JavaScript               6 mins              █████░░░░░░░░░░░░░░░░░░░░   20.23% 
Bash                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.44%

🔥 Editors: 
VS Code                  31 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
lavy                     31 mins             ████████████████████████░   98.4% 
kreativ.inc              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.6%

💻 Operating System: 
Linux                    31 mins             █████████████████████████   100.0%

```


 Last Updated on 15/12/2023 18:35:16 UTC
<!--END_SECTION:waka-->
