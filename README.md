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
![Code Time](http://img.shields.io/badge/Code%20Time-730%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 464 Contributions in the Year 2023
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
JavaScript               6 hrs 55 mins       █████████████░░░░░░░░░░░░   52.62% 
Python                   5 hrs 10 mins       █████████░░░░░░░░░░░░░░░░   39.34% 
HTML                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.53% 
Bash                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.43% 
CSS                      8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.07%

🔥 Editors: 
VS Code                  13 hrs 9 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              5 hrs 44 mins       ███████████░░░░░░░░░░░░░░   43.61% 
travel-service-api       4 hrs 35 mins       ████████░░░░░░░░░░░░░░░░░   34.96% 
wabo.bj                  1 hr 48 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.8% 
baba-mandef-api          50 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.36% 
quatro                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.28%

💻 Operating System: 
Linux                    13 hrs 9 mins       █████████████████████████   100.0%

```


 Last Updated on 08/08/2023 18:33:31 UTC
<!--END_SECTION:waka-->
