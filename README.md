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
Python                   4 hrs 5 mins        ███████████████░░░░░░░░░░   59.56% 
JavaScript               42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.27% 
YAML                     39 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.5% 
Nginx configuration file 36 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.73% 
Docker                   23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.66%

🔥 Editors: 
VS Code                  6 hrs 52 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef-api          2 hrs 1 min         ███████░░░░░░░░░░░░░░░░░░   29.5% 
travel-service-api       1 hr 58 mins        ███████░░░░░░░░░░░░░░░░░░   28.64% 
quatro                   1 hr 12 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.56% 
air-codes                57 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.92% 
api.isere.com            42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.38%

💻 Operating System: 
Linux                    6 hrs 52 mins       █████████████████████████   100.0%

```


 Last Updated on 25/08/2023 18:33:43 UTC
<!--END_SECTION:waka-->
