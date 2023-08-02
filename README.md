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
![Code Time](http://img.shields.io/badge/Code%20Time-720%20hrs%2043%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 433 Contributions in the Year 2023
 > 
> 📦 106.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 45 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   10 hrs 26 mins      █████████████░░░░░░░░░░░░   55.36% 
JavaScript               7 hrs 39 mins       ██████████░░░░░░░░░░░░░░░   40.61% 
Bash                     41 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.63% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32% 
HTML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  18 hrs 52 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              7 hrs 39 mins       ██████████░░░░░░░░░░░░░░░   40.57% 
baba-mandef-api          6 hrs 48 mins       █████████░░░░░░░░░░░░░░░░   36.11% 
travel-service-api       4 hrs 22 mins       █████░░░░░░░░░░░░░░░░░░░░   23.17% 
wabo.bj                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11% 
quatro                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

💻 Operating System: 
Linux                    18 hrs 52 mins      █████████████████████████   100.0%

```


 Last Updated on 02/08/2023 18:34:06 UTC
<!--END_SECTION:waka-->
