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
Python                   2 hrs 6 mins        █████████████░░░░░░░░░░░░   51.76% 
JavaScript               42 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.41% 
Nginx configuration file 32 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.52% 
YAML                     19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.93% 
JSON                     11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.57%

🔥 Editors: 
VS Code                  4 hrs 3 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
travel-service-api       1 hr 58 mins        ████████████░░░░░░░░░░░░░   48.54% 
baba-mandef-api          1 hr 1 min          ██████░░░░░░░░░░░░░░░░░░░   25.36% 
air-codes                57 mins             ██████░░░░░░░░░░░░░░░░░░░   23.59% 
quatro                   6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.51%

💻 Operating System: 
Linux                    4 hrs 3 mins        █████████████████████████   100.0%

```


 Last Updated on 29/08/2023 18:34:09 UTC
<!--END_SECTION:waka-->
