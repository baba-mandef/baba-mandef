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
![Code Time](http://img.shields.io/badge/Code%20Time-797%20hrs%207%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 580 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 40 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     4 hrs 51 mins       █████████████░░░░░░░░░░░░   53.1% 
JavaScript               1 hr 59 mins        █████░░░░░░░░░░░░░░░░░░░░   21.76% 
Python                   1 hr 16 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.89% 
Vue.js                   44 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.11% 
CSS                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.94%

🔥 Editors: 
VS Code                  9 hrs 9 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      5 hrs 34 mins       ███████████████░░░░░░░░░░   60.83% 
_                        2 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   26.53% 
default                  1 hr 9 mins         ███░░░░░░░░░░░░░░░░░░░░░░   12.64%

💻 Operating System: 
Linux                    9 hrs 9 mins        █████████████████████████   100.0%

```


 Last Updated on 19/10/2023 18:35:09 UTC
<!--END_SECTION:waka-->
