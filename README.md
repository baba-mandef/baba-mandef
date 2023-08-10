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
JavaScript               7 hrs 49 mins       ██████████████░░░░░░░░░░░   59.15% 
Python                   4 hrs 1 min         ███████░░░░░░░░░░░░░░░░░░   30.42% 
HTML                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.1% 
CSS                      23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.96% 
Bash                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.42%

🔥 Editors: 
VS Code                  13 hrs 13 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
wabo.bj                  6 hrs 13 mins       ███████████░░░░░░░░░░░░░░   47.13% 
travel-service-api       3 hrs 59 mins       ███████░░░░░░░░░░░░░░░░░░   30.13% 
baba-mandef              2 hrs 32 mins       ████░░░░░░░░░░░░░░░░░░░░░   19.22% 
baba-mandef-api          17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26% 
quatro                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.27%

💻 Operating System: 
Linux                    13 hrs 13 mins      █████████████████████████   100.0%

```


 Last Updated on 10/08/2023 18:34:00 UTC
<!--END_SECTION:waka-->
