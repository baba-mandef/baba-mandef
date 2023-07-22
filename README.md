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
                           'Telegram': 'ptahemdjehuty',
                           'Mail':'pariso03henri@gmail.com',
                        }
         }
        return Response(ptahemdjehuty, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-689%20hrs%2055%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 340 Contributions in the Year 2023
 > 
> 📦 89.3 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 40 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               8 hrs 8 mins        ███████████████░░░░░░░░░░   59.82% 
Python                   4 hrs 56 mins       █████████░░░░░░░░░░░░░░░░   36.32% 
Bash                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.75% 
Other                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.95% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.86%

🔥 Editors: 
VS Code                  13 hrs 36 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              8 hrs 17 mins       ███████████████░░░░░░░░░░   60.97% 
baba-mandef-api          3 hrs 8 mins        █████░░░░░░░░░░░░░░░░░░░░   23.13% 
quatro                   2 hrs 9 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.91%

💻 Operating System: 
Linux                    13 hrs 36 mins      █████████████████████████   100.0%

```


 Last Updated on 22/07/2023 18:33:55 UTC
<!--END_SECTION:waka-->
