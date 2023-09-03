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
![Code Time](http://img.shields.io/badge/Code%20Time-751%20hrs%2051%20mins-blue)

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
Python                   40 mins             ███████████████████████░░   92.34% 
Gettext Catalog          2 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.54% 
Kotlin                   1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   3.09% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
PyCharmCore              39 mins             ██████████████████████░░░   89.47% 
VS Code                  3 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   7.44% 
Android Studio           1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   3.09%

🐱‍💻 Projects: 
quatro                   42 mins             ████████████████████████░   96.91% 
course                   1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   3.09%

💻 Operating System: 
Linux                    44 mins             █████████████████████████   100.0%

```


 Last Updated on 03/09/2023 18:33:53 UTC
<!--END_SECTION:waka-->
