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
![Code Time](http://img.shields.io/badge/Code%20Time-873%20hrs%2035%20mins-blue)

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
Python                   11 hrs 36 mins      ████████░░░░░░░░░░░░░░░░░   34.6% 
HTML                     9 hrs 37 mins       ███████░░░░░░░░░░░░░░░░░░   28.67% 
Vue.js                   8 hrs 50 mins       ██████░░░░░░░░░░░░░░░░░░░   26.36% 
CSS                      1 hr 37 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.86% 
TypeScript               42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.1%

🔥 Editors: 
VS Code                  33 hrs 33 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
template_01              12 hrs 6 mins       █████████░░░░░░░░░░░░░░░░   36.06% 
korbo.fr                 9 hrs 33 mins       ███████░░░░░░░░░░░░░░░░░░   28.49% 
api.korbo.fr             8 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   25.08% 
quatro                   3 hrs 26 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   10.28% 
sub                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

💻 Operating System: 
Linux                    33 hrs 33 mins      █████████████████████████   100.0%

```


 Last Updated on 16/11/2023 18:35:42 UTC
<!--END_SECTION:waka-->
