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
![Code Time](http://img.shields.io/badge/Code%20Time-779%20hrs%2013%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 565 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 40 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   1 hr 33 mins        ██████████████████░░░░░░░   74.17% 
Text                     32 mins             ██████░░░░░░░░░░░░░░░░░░░   25.83%

🔥 Editors: 
VS Code                  1 hr 56 mins        ███████████████████████░░   92.53% 
PyCharmCore              9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   7.47%

🐱‍💻 Projects: 
iwedioro                 1 hr 56 mins        ███████████████████████░░   92.53% 
travel-service-api       8 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.69% 
quatro                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77%

💻 Operating System: 
Linux                    2 hrs 6 mins        █████████████████████████   100.0%

```


 Last Updated on 30/09/2023 18:33:40 UTC
<!--END_SECTION:waka-->
