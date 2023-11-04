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
![Code Time](http://img.shields.io/badge/Code%20Time-821%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

**🐱 My GitHub Data** 

> 🏆 590 Contributions in the Year 2023
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
Python                   13 hrs 43 mins      ████████████████████████░   99.12% 
HTML                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56% 
CSS                      2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
VS Code                  13 hrs 50 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   7 hrs 33 mins       █████████████░░░░░░░░░░░░   54.58% 
api.korbo.fr             6 hrs 10 mins       ███████████░░░░░░░░░░░░░░   44.57% 
sub                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.85%

💻 Operating System: 
Linux                    13 hrs 50 mins      █████████████████████████   100.0%

```


 Last Updated on 04/11/2023 18:33:27 UTC
<!--END_SECTION:waka-->
