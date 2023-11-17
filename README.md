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
HTML                     11 hrs 30 mins      ██████████░░░░░░░░░░░░░░░   39.96% 
Vue.js                   8 hrs 47 mins       ███████░░░░░░░░░░░░░░░░░░   30.52% 
Python                   5 hrs 13 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.17% 
CSS                      1 hr 39 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.73% 
TypeScript               42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.45%

🔥 Editors: 
VS Code                  28 hrs 47 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
template_01              14 hrs              ████████████░░░░░░░░░░░░░   48.64% 
korbo.fr                 9 hrs 30 mins       ████████░░░░░░░░░░░░░░░░░   33.0% 
api.korbo.fr             4 hrs 28 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.53% 
quatro                   47 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.74% 
sub                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

💻 Operating System: 
Linux                    28 hrs 47 mins      █████████████████████████   100.0%

```


 Last Updated on 17/11/2023 18:35:23 UTC
<!--END_SECTION:waka-->
