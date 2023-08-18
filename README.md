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
![Code Time](http://img.shields.io/badge/Code%20Time-742%20hrs%2034%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 481 Contributions in the Year 2023
 > 
> 📦 98.5 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 37 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   4 hrs 22 mins       █████████████████░░░░░░░░   69.06% 
JavaScript               1 hr 31 mins        ██████░░░░░░░░░░░░░░░░░░░   24.16% 
Git Config               8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.28% 
CSS                      5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.52% 
Bash                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.45%

🔥 Editors: 
VS Code                  6 hrs 19 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   4 hrs 40 mins       ██████████████████░░░░░░░   73.95% 
wabo.bj                  1 hr 38 mins        ██████░░░░░░░░░░░░░░░░░░░   26.05%

💻 Operating System: 
Linux                    6 hrs 19 mins       █████████████████████████   100.0%

```


 Last Updated on 18/08/2023 18:34:16 UTC
<!--END_SECTION:waka-->
