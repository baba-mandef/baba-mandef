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
![Code Time](http://img.shields.io/badge/Code%20Time-728%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 452 Contributions in the Year 2023
 > 
> 📦 97.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 36 Public Repositories 
 > 
> 🔑 13 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               8 hrs 42 mins       ███████████████░░░░░░░░░░   59.68% 
Python                   5 hrs 1 min         ████████░░░░░░░░░░░░░░░░░   34.42% 
HTML                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26% 
Bash                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.64% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89%

🔥 Editors: 
VS Code                  14 hrs 35 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              7 hrs 50 mins       █████████████░░░░░░░░░░░░   53.74% 
travel-service-api       3 hrs 49 mins       ██████░░░░░░░░░░░░░░░░░░░   26.26% 
wabo.bj                  1 hr 29 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.2% 
baba-mandef-api          1 hr 15 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.65% 
quatro                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.15%

💻 Operating System: 
Linux                    14 hrs 35 mins      █████████████████████████   100.0%

```


 Last Updated on 07/08/2023 18:33:31 UTC
<!--END_SECTION:waka-->
