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
![Code Time](http://img.shields.io/badge/Code%20Time-755%20hrs%2023%20mins-blue)

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
Python                   6 hrs 6 mins        ███████████████████████░░   92.51% 
Dart                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.98% 
XML                      8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.19% 
Kotlin                   8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.06% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.24%

🔥 Editors: 
PyCharmCore              6 hrs 6 mins        ███████████████████████░░   92.51% 
Android Studio           29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.49%

🐱‍💻 Projects: 
quatro                   6 hrs 6 mins        ███████████████████████░░   92.51% 
dema                     20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.19% 
course                   8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.06% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.24%

💻 Operating System: 
Linux                    6 hrs 35 mins       █████████████████████████   100.0%

```


 Last Updated on 06/09/2023 18:34:06 UTC
<!--END_SECTION:waka-->
