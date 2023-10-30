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
![Code Time](http://img.shields.io/badge/Code%20Time-808%20hrs%2030%20mins-blue)

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
Python                   3 hrs 10 mins       ████████████████████████░   96.21% 
HTML                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.37% 
CSS                      2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.19% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  2 hrs 18 mins       █████████████████░░░░░░░░   69.89% 
PyCharmCore              59 mins             ███████░░░░░░░░░░░░░░░░░░   30.11%

🐱‍💻 Projects: 
quatro                   3 hrs 10 mins       ████████████████████████░   96.43% 
sub                      7 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.57%

💻 Operating System: 
Linux                    3 hrs 17 mins       █████████████████████████   100.0%

```


 Last Updated on 30/10/2023 18:35:15 UTC
<!--END_SECTION:waka-->
