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
![Code Time](http://img.shields.io/badge/Code%20Time-868%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

**🐱 My GitHub Data** 

> 🏆 602 Contributions in the Year 2023
 > 
> 📦 98.7 kB Used in GitHub's Storage 
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
Python                   14 hrs 3 mins       ███████████░░░░░░░░░░░░░░   44.91% 
Vue.js                   9 hrs 15 mins       ███████░░░░░░░░░░░░░░░░░░   29.59% 
HTML                     4 hrs 13 mins       ███░░░░░░░░░░░░░░░░░░░░░░   13.51% 
CSS                      1 hr 35 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.11% 
TypeScript               48 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.58%

🔥 Editors: 
VS Code                  31 hrs 18 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
korbo.fr                 10 hrs 5 mins       ████████░░░░░░░░░░░░░░░░░   32.2% 
api.korbo.fr             8 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   26.88% 
template_01              6 hrs 39 mins       █████░░░░░░░░░░░░░░░░░░░░   21.28% 
quatro                   6 hrs 7 mins        █████░░░░░░░░░░░░░░░░░░░░   19.55% 
sub                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

💻 Operating System: 
Linux                    31 hrs 18 mins      █████████████████████████   100.0%

```


 Last Updated on 15/11/2023 18:33:52 UTC
<!--END_SECTION:waka-->
