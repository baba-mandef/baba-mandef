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
![Code Time](http://img.shields.io/badge/Code%20Time-747%20hrs%204%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 497 Contributions in the Year 2023
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
Python                   5 hrs 42 mins       █████████████████░░░░░░░░   67.6% 
JavaScript               1 hr 26 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.16% 
Docker                   22 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.49% 
YAML                     19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.93% 
Bash                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95%

🔥 Editors: 
VS Code                  8 hrs 26 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
quatro                   5 hrs 9 mins        ███████████████░░░░░░░░░░   61.11% 
wabo.bj                  1 hr 34 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.57% 
baba-mandef-api          1 hr                ███░░░░░░░░░░░░░░░░░░░░░░   11.85% 
api.isere.com            42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.46%

💻 Operating System: 
Linux                    8 hrs 26 mins       █████████████████████████   100.0%

```


 Last Updated on 22/08/2023 18:33:57 UTC
<!--END_SECTION:waka-->
