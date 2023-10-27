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
![Code Time](http://img.shields.io/badge/Code%20Time-806%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

**🐱 My GitHub Data** 

> 🏆 581 Contributions in the Year 2023
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
Python                   5 hrs 19 mins       ████████████████░░░░░░░░░   64.26% 
HTML                     2 hrs 55 mins       ████████░░░░░░░░░░░░░░░░░   35.37% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
VS Code                  7 hrs 17 mins       ██████████████████████░░░   88.02% 
PyCharmCore              59 mins             ███░░░░░░░░░░░░░░░░░░░░░░   11.98%

🐱‍💻 Projects: 
sub                      5 hrs 14 mins       ███████████████░░░░░░░░░░   63.22% 
quatro                   2 hrs 51 mins       ████████░░░░░░░░░░░░░░░░░   34.42% 
default                  11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.37%

💻 Operating System: 
Linux                    8 hrs 17 mins       █████████████████████████   100.0%

```


 Last Updated on 27/10/2023 18:34:12 UTC
<!--END_SECTION:waka-->
