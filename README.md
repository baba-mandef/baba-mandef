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

> 🏆 500 Contributions in the Year 2023
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
Python                   2 hrs 13 mins       ███████████░░░░░░░░░░░░░░   44.49% 
JavaScript               42 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.12% 
YAML                     39 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.06% 
Nginx configuration file 36 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.0% 
Docker                   23 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.78%

🔥 Editors: 
VS Code                  5 hrs               █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef-api          2 hrs 1 min         ██████████░░░░░░░░░░░░░░░   40.55% 
travel-service-api       1 hr 58 mins        █████████░░░░░░░░░░░░░░░░   39.37% 
air-codes                57 mins             ████░░░░░░░░░░░░░░░░░░░░░   19.14% 
quatro                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94%

💻 Operating System: 
Linux                    5 hrs               █████████████████████████   100.0%

```


 Last Updated on 27/08/2023 18:33:58 UTC
<!--END_SECTION:waka-->
