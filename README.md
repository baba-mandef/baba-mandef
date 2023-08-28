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
![Code Time](http://img.shields.io/badge/Code%20Time-751%20hrs%2035%20mins-blue)

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
Python                   2 hrs 11 mins       ████████████░░░░░░░░░░░░░   48.63% 
JavaScript               42 mins             ████░░░░░░░░░░░░░░░░░░░░░   15.72% 
Nginx configuration file 35 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.09% 
YAML                     22 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.48% 
Docker                   17 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.31%

🔥 Editors: 
VS Code                  4 hrs 29 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
travel-service-api       1 hr 58 mins        ███████████░░░░░░░░░░░░░░   43.84% 
baba-mandef-api          1 hr 31 mins        ████████░░░░░░░░░░░░░░░░░   33.8% 
air-codes                57 mins             █████░░░░░░░░░░░░░░░░░░░░   21.31% 
quatro                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.05%

💻 Operating System: 
Linux                    4 hrs 29 mins       █████████████████████████   100.0%

```


 Last Updated on 28/08/2023 18:33:59 UTC
<!--END_SECTION:waka-->
