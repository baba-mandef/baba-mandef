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
![Code Time](http://img.shields.io/badge/Code%20Time-875%20hrs%2029%20mins-blue)

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
HTML                     16 hrs 45 mins      █████████████░░░░░░░░░░░░   53.46% 
Python                   6 hrs 51 mins       █████░░░░░░░░░░░░░░░░░░░░   21.88% 
Vue.js                   4 hrs 22 mins       ███░░░░░░░░░░░░░░░░░░░░░░   13.95% 
CSS                      1 hr 36 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.14% 
JavaScript               56 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.01%

🔥 Editors: 
VS Code                  31 hrs 21 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
template_01              13 hrs 23 mins      ██████████░░░░░░░░░░░░░░░   42.71% 
sub                      13 hrs 2 mins       ██████████░░░░░░░░░░░░░░░   41.59% 
korbo.fr                 4 hrs 37 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.76% 
baba-mandef-api          15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.83% 
api.korbo.fr             2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

💻 Operating System: 
Linux                    31 hrs 21 mins      █████████████████████████   100.0%

```


 Last Updated on 20/11/2023 18:36:21 UTC
<!--END_SECTION:waka-->
