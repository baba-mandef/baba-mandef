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
![Code Time](http://img.shields.io/badge/Code%20Time-752%20hrs%2059%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 506 Contributions in the Year 2023
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
Python                   3 hrs 28 mins       ███████████████████████░░   92.85% 
Kotlin                   8 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.62% 
XML                      6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.78% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43% 
Dart                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.27%

🔥 Editors: 
PyCharmCore              3 hrs 28 mins       ███████████████████████░░   92.86% 
Android Studio           16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.14%

🐱‍💻 Projects: 
quatro                   3 hrs 28 mins       ███████████████████████░░   92.86% 
course                   8 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.62% 
dema                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.09% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

💻 Operating System: 
Linux                    3 hrs 44 mins       █████████████████████████   100.0%

```


 Last Updated on 05/09/2023 18:34:05 UTC
<!--END_SECTION:waka-->
