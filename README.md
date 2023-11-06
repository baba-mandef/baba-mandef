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
![Code Time](http://img.shields.io/badge/Code%20Time-826%20hrs%2055%20mins-blue)

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
Python                   17 hrs 44 mins      ████████████████████████░   97.0% 
Vue.js                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.98% 
Other                    8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.78% 
HTML                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43% 
TSConfig                 2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26%

🔥 Editors: 
VS Code                  18 hrs 17 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
api.korbo.fr             9 hrs 36 mins       █████████████░░░░░░░░░░░░   52.47% 
quatro                   8 hrs 10 mins       ███████████░░░░░░░░░░░░░░   44.67% 
korbo.fr                 22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.09% 
sub                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.64% 
korbo                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12%

💻 Operating System: 
Linux                    18 hrs 17 mins      █████████████████████████   100.0%

```


 Last Updated on 06/11/2023 18:35:24 UTC
<!--END_SECTION:waka-->
