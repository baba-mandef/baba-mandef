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
![Code Time](http://img.shields.io/badge/Code%20Time-746%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 487 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
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
Python                   6 hrs 16 mins       ██████████████████░░░░░░░   72.1% 
JavaScript               1 hr 31 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.54% 
YAML                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.13% 
Bash                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.89% 
Git Config               8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.66%

🔥 Editors: 
VS Code                  8 hrs 42 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   5 hrs 50 mins       ████████████████░░░░░░░░░   67.03% 
wabo.bj                  1 hr 38 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.92% 
api.isere.com            42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.2% 
baba-mandef-api          30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.86%

💻 Operating System: 
Linux                    8 hrs 42 mins       █████████████████████████   100.0%

```


 Last Updated on 21/08/2023 18:33:47 UTC
<!--END_SECTION:waka-->
