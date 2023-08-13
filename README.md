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
![Code Time](http://img.shields.io/badge/Code%20Time-738%20hrs%2021%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 477 Contributions in the Year 2023
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
JavaScript               6 hrs 39 mins       ████████████████░░░░░░░░░   65.42% 
Python                   2 hrs 42 mins       ██████░░░░░░░░░░░░░░░░░░░   26.57% 
Bash                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15% 
CSS                      15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.57% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.07%

🔥 Editors: 
VS Code                  10 hrs 10 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
wabo.bj                  4 hrs 44 mins       ███████████░░░░░░░░░░░░░░   46.6% 
travel-service-api       2 hrs 50 mins       ███████░░░░░░░░░░░░░░░░░░   27.84% 
baba-mandef              2 hrs 18 mins       █████░░░░░░░░░░░░░░░░░░░░   22.62% 
baba-mandef-api          17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.94%

💻 Operating System: 
Linux                    10 hrs 10 mins      █████████████████████████   100.0%

```


 Last Updated on 13/08/2023 18:33:52 UTC
<!--END_SECTION:waka-->
