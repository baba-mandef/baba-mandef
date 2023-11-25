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
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-891%20hrs%2047%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 602 Contributions in the Year 2023
 > 
> 📦 98.7 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 42 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   8 hrs 26 mins       ███████████████░░░░░░░░░░   60.59% 
HTML                     3 hrs 52 mins       ███████░░░░░░░░░░░░░░░░░░   27.88% 
JavaScript               1 hr                █░░░░░░░░░░░░░░░░░░░░░░░░   7.28% 
Text                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.7% 
CSS                      12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.46%

🔥 Editors: 
VS Code                  13 hrs 55 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      12 hrs 18 mins      ██████████████████████░░░   88.44% 
lavy                     1 hr 20 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.68% 
baba-mandef-api          15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.88%

💻 Operating System: 
Linux                    13 hrs 55 mins      █████████████████████████   100.0%

```


 Last Updated on 25/11/2023 18:33:42 UTC
<!--END_SECTION:waka-->
