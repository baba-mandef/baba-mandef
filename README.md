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

> 🏆 481 Contributions in the Year 2023
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
Python                   6 hrs 14 mins       ███████████████████░░░░░░   76.09% 
JavaScript               1 hr 31 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.63% 
Git Config               8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.76% 
CSS                      5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.17% 
Bash                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12%

🔥 Editors: 
VS Code                  8 hrs 12 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   5 hrs 50 mins       █████████████████░░░░░░░░   71.2% 
wabo.bj                  1 hr 38 mins        █████░░░░░░░░░░░░░░░░░░░░   20.09% 
api.isere.com            42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.71%

💻 Operating System: 
Linux                    8 hrs 12 mins       █████████████████████████   100.0%

```


 Last Updated on 20/08/2023 18:33:51 UTC
<!--END_SECTION:waka-->
