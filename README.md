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
![Code Time](http://img.shields.io/badge/Code%20Time-768%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 540 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
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
Python                   6 hrs 40 mins       ███████████████████░░░░░░   79.36% 
YAML                     1 hr 6 mins         ███░░░░░░░░░░░░░░░░░░░░░░   13.25% 
Nginx Configuration      13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.66% 
Nginx configuration file 9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.8% 
XML                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.42%

🔥 Editors: 
PyCharmCore              8 hrs 14 mins       ████████████████████████░   98.0% 
VS Code                  10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.0%

🐱‍💻 Projects: 
travel-service-api       5 hrs 6 mins        ███████████████░░░░░░░░░░   60.81% 
baba-mandef-api          2 hrs 11 mins       ██████░░░░░░░░░░░░░░░░░░░   26.13% 
quatro                   1 hr 5 mins         ███░░░░░░░░░░░░░░░░░░░░░░   13.06%

💻 Operating System: 
Linux                    8 hrs 24 mins       █████████████████████████   100.0%

```


 Last Updated on 15/09/2023 18:34:06 UTC
<!--END_SECTION:waka-->
