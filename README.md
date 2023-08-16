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
![Code Time](http://img.shields.io/badge/Code%20Time-739%20hrs%207%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 477 Contributions in the Year 2023
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
Python                   45 mins             ██████████████████████░░░   90.37% 
JavaScript               4 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   9.63%

🔥 Editors: 
VS Code                  49 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   40 mins             ████████████████████░░░░░   81.83% 
wabo.bj                  4 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   9.63% 
travel-service-api       4 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   8.55%

💻 Operating System: 
Linux                    49 mins             █████████████████████████   100.0%

```


 Last Updated on 16/08/2023 18:33:47 UTC
<!--END_SECTION:waka-->
