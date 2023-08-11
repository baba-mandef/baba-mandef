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
![Code Time](http://img.shields.io/badge/Code%20Time-738%20hrs%2017%20mins-blue)

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
JavaScript               7 hrs 49 mins       ██████████████░░░░░░░░░░░   58.83% 
Python                   4 hrs 5 mins        ███████░░░░░░░░░░░░░░░░░░   30.79% 
HTML                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.08% 
CSS                      23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.95% 
Bash                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.41%

🔥 Editors: 
VS Code                  13 hrs 17 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
wabo.bj                  6 hrs 13 mins       ███████████░░░░░░░░░░░░░░   46.87% 
travel-service-api       4 hrs 3 mins        ███████░░░░░░░░░░░░░░░░░░   30.5% 
baba-mandef              2 hrs 32 mins       ████░░░░░░░░░░░░░░░░░░░░░   19.11% 
baba-mandef-api          17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.25% 
quatro                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.26%

💻 Operating System: 
Linux                    13 hrs 17 mins      █████████████████████████   100.0%

```


 Last Updated on 11/08/2023 18:33:50 UTC
<!--END_SECTION:waka-->
