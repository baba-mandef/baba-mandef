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
![Code Time](http://img.shields.io/badge/Code%20Time-748%20hrs%2039%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 499 Contributions in the Year 2023
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
Python                   5 hrs 17 mins       ██████████████░░░░░░░░░░░   58.8% 
JavaScript               1 hr 21 mins        ███░░░░░░░░░░░░░░░░░░░░░░   15.14% 
YAML                     39 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.27% 
Nginx configuration file 36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.68% 
Docker                   23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.33%

🔥 Editors: 
VS Code                  9 hrs               █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   2 hrs 33 mins       ███████░░░░░░░░░░░░░░░░░░   28.48% 
baba-mandef-api          2 hrs 1 min         █████░░░░░░░░░░░░░░░░░░░░   22.56% 
travel-service-api       1 hr 58 mins        █████░░░░░░░░░░░░░░░░░░░░   21.91% 
air-codes                57 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.65% 
wabo.bj                  45 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.47%

💻 Operating System: 
Linux                    9 hrs               █████████████████████████   100.0%

```


 Last Updated on 24/08/2023 18:34:05 UTC
<!--END_SECTION:waka-->
