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
![Code Time](http://img.shields.io/badge/Code%20Time-725%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 447 Contributions in the Year 2023
 > 
> 📦 124.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 44 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   7 hrs 46 mins       ████████████░░░░░░░░░░░░░   48.77% 
JavaScript               6 hrs 57 mins       ███████████░░░░░░░░░░░░░░   43.61% 
Bash                     36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.82% 
HTML                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.07% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.82%

🔥 Editors: 
VS Code                  15 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              6 hrs 3 mins        █████████░░░░░░░░░░░░░░░░   37.93% 
baba-mandef-api          4 hrs 24 mins       ███████░░░░░░░░░░░░░░░░░░   27.68% 
travel-service-api       3 hrs 49 mins       ██████░░░░░░░░░░░░░░░░░░░   24.01% 
wabo.bj                  1 hr 29 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.33% 
quatro                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.05%

💻 Operating System: 
Linux                    15 hrs 57 mins      █████████████████████████   100.0%

```


 Last Updated on 05/08/2023 18:33:42 UTC
<!--END_SECTION:waka-->
