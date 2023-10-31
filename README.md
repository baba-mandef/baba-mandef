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
![Code Time](http://img.shields.io/badge/Code%20Time-808%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

**🐱 My GitHub Data** 

> 🏆 583 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 41 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   4 hrs 52 mins       ████████████████████████░   97.51% 
HTML                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.56% 
CSS                      2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.79% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
VS Code                  5 hrs               █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   4 hrs 53 mins       ████████████████████████░   97.65% 
sub                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.35%

💻 Operating System: 
Linux                    5 hrs               █████████████████████████   100.0%

```


 Last Updated on 31/10/2023 18:34:46 UTC
<!--END_SECTION:waka-->
