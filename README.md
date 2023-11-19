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
HTML                     16 hrs 35 mins      ███████████░░░░░░░░░░░░░░   45.16% 
Vue.js                   8 hrs 47 mins       ██████░░░░░░░░░░░░░░░░░░░   23.93% 
Python                   7 hrs 33 mins       █████░░░░░░░░░░░░░░░░░░░░   20.59% 
CSS                      1 hr 36 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.38% 
JavaScript               56 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.57%

🔥 Editors: 
VS Code                  36 hrs 43 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
template_01              13 hrs 23 mins      █████████░░░░░░░░░░░░░░░░   36.46% 
sub                      11 hrs 29 mins      ███████░░░░░░░░░░░░░░░░░░   31.29% 
korbo.fr                 9 hrs 30 mins       ██████░░░░░░░░░░░░░░░░░░░   25.87% 
api.korbo.fr             2 hrs 1 min         █░░░░░░░░░░░░░░░░░░░░░░░░   5.53% 
baba-mandef-api          15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.71%

💻 Operating System: 
Linux                    36 hrs 43 mins      █████████████████████████   100.0%

```


 Last Updated on 19/11/2023 18:33:32 UTC
<!--END_SECTION:waka-->
