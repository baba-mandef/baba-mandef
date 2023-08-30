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
![Code Time](http://img.shields.io/badge/Code%20Time-751%20hrs%2039%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 501 Contributions in the Year 2023
 > 
> 📦 98.5 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 38 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   1 hr 59 mins        ████████████████░░░░░░░░░   66.77% 
JavaScript               42 mins             ██████░░░░░░░░░░░░░░░░░░░   23.69% 
JSON                     11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.22% 
Markdown                 3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.17% 
Gettext Catalog          2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12%

🔥 Editors: 
VS Code                  2 hrs 59 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
travel-service-api       1 hr 58 mins        ████████████████░░░░░░░░░   66.06% 
air-codes                57 mins             ████████░░░░░░░░░░░░░░░░░   32.11% 
quatro                   3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.83%

💻 Operating System: 
Linux                    2 hrs 59 mins       █████████████████████████   100.0%

```


 Last Updated on 30/08/2023 18:34:34 UTC
<!--END_SECTION:waka-->
