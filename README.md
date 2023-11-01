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
![Code Time](http://img.shields.io/badge/Code%20Time-811%20hrs%2052%20mins-blue)

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
Python                   5 hrs 53 mins       ████████████████████████░   97.93% 
HTML                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.3% 
CSS                      2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.65% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
VS Code                  6 hrs 1 min         █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   5 hrs 54 mins       ████████████████████████░   98.05% 
sub                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95%

💻 Operating System: 
Linux                    6 hrs 1 min         █████████████████████████   100.0%

```


 Last Updated on 01/11/2023 18:34:41 UTC
<!--END_SECTION:waka-->
