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
![Code Time](http://img.shields.io/badge/Code%20Time-733%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 476 Contributions in the Year 2023
 > 
> 📦 107.2 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 36 Public Repositories 
 > 
> 🔑 12 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               10 hrs 16 mins      ███████████████░░░░░░░░░░   62.72% 
Python                   4 hrs 42 mins       ███████░░░░░░░░░░░░░░░░░░   28.77% 
HTML                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.5% 
CSS                      23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.39% 
Bash                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.96%

🔥 Editors: 
VS Code                  16 hrs 22 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
wabo.bj                  6 hrs 13 mins       █████████░░░░░░░░░░░░░░░░   38.05% 
baba-mandef              5 hrs               ███████░░░░░░░░░░░░░░░░░░   30.56% 
travel-service-api       4 hrs 20 mins       ██████░░░░░░░░░░░░░░░░░░░   26.56% 
baba-mandef-api          37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.8% 
quatro                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.03%

💻 Operating System: 
Linux                    16 hrs 22 mins      █████████████████████████   100.0%

```


 Last Updated on 09/08/2023 18:36:15 UTC
<!--END_SECTION:waka-->
