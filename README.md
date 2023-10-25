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
![Code Time](http://img.shields.io/badge/Code%20Time-806%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

**🐱 My GitHub Data** 

> 🏆 581 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 41 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     5 hrs 19 mins       █████████████░░░░░░░░░░░░   55.35% 
Python                   3 hrs 49 mins       ██████████░░░░░░░░░░░░░░░   39.69% 
CSS                      23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.02% 
JavaScript               5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.93% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
VS Code                  8 hrs 37 mins       ██████████████████████░░░   89.69% 
PyCharmCore              59 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.31%

🐱‍💻 Projects: 
sub                      8 hrs 1 min         ████████████████████░░░░░   83.31% 
quatro                   1 hr 13 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.69% 
default                  23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.0%

💻 Operating System: 
Linux                    9 hrs 37 mins       █████████████████████████   100.0%

```


 Last Updated on 25/10/2023 18:34:19 UTC
<!--END_SECTION:waka-->
