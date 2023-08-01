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
![Code Time](http://img.shields.io/badge/Code%20Time-716%20hrs%2011%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 424 Contributions in the Year 2023
 > 
> 📦 106.5 kB Used in GitHub's Storage 
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
Python                   11 hrs 45 mins      █████████████░░░░░░░░░░░░   54.15% 
JavaScript               9 hrs 5 mins        ██████████░░░░░░░░░░░░░░░   41.83% 
Bash                     41 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15% 
JSON                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.41% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28%

🔥 Editors: 
VS Code                  21 hrs 43 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              9 hrs 6 mins        ██████████░░░░░░░░░░░░░░░   41.91% 
baba-mandef-api          6 hrs 36 mins       ███████░░░░░░░░░░░░░░░░░░   30.38% 
travel-service-api       4 hrs 56 mins       █████░░░░░░░░░░░░░░░░░░░░   22.76% 
followtrainbot           57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.4% 
planetech_market         5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.42%

💻 Operating System: 
Linux                    21 hrs 43 mins      █████████████████████████   100.0%

```


 Last Updated on 01/08/2023 18:33:52 UTC
<!--END_SECTION:waka-->
