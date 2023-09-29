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
![Code Time](http://img.shields.io/badge/Code%20Time-778%20hrs%2013%20mins-blue)

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
Python                   43 mins             ██████████████░░░░░░░░░░░   57.15% 
Text                     32 mins             ██████████░░░░░░░░░░░░░░░   42.85%

🔥 Editors: 
VS Code                  59 mins             ███████████████████░░░░░░   78.65% 
PyCharmCore              16 mins             █████░░░░░░░░░░░░░░░░░░░░   21.35%

🐱‍💻 Projects: 
iwedioro                 59 mins             ███████████████████░░░░░░   78.65% 
travel-service-api       15 mins             █████░░░░░░░░░░░░░░░░░░░░   20.07% 
quatro                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.28%

💻 Operating System: 
Linux                    1 hr 16 mins        █████████████████████████   100.0%

```


 Last Updated on 29/09/2023 18:35:02 UTC
<!--END_SECTION:waka-->
