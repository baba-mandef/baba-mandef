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
![Code Time](http://img.shields.io/badge/Code%20Time-747%20hrs%2035%20mins-blue)

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
Python                   5 hrs 49 mins       ███████████████░░░░░░░░░░   61.1% 
JavaScript               1 hr 26 mins        ███░░░░░░░░░░░░░░░░░░░░░░   15.21% 
YAML                     39 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.87% 
Nginx configuration file 36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.31% 
Docker                   23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.09%

🔥 Editors: 
VS Code                  9 hrs 31 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   5 hrs 12 mins       █████████████░░░░░░░░░░░░   54.7% 
baba-mandef-api          2 hrs 1 min         █████░░░░░░░░░░░░░░░░░░░░   21.33% 
wabo.bj                  1 hr 34 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.47% 
api.isere.com            42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.5%

💻 Operating System: 
Linux                    9 hrs 31 mins       █████████████████████████   100.0%

```


 Last Updated on 23/08/2023 18:34:07 UTC
<!--END_SECTION:waka-->
