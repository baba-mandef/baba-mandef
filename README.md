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
![Code Time](http://img.shields.io/badge/Code%20Time-777%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 562 Contributions in the Year 2023
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
Python                   2 hrs 28 mins       ████████████░░░░░░░░░░░░░   48.25% 
Nginx configuration file 1 hr 9 mins         █████░░░░░░░░░░░░░░░░░░░░   22.52% 
YAML                     38 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.48% 
Markdown                 34 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.29% 
JavaScript               8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.72%

🔥 Editors: 
VS Code                  3 hrs 16 mins       ████████████████░░░░░░░░░   63.8% 
PyCharmCore              1 hr 51 mins        █████████░░░░░░░░░░░░░░░░   36.2%

🐱‍💻 Projects: 
travel-service-api       2 hrs 13 mins       ██████████░░░░░░░░░░░░░░░   43.23% 
baba-mandef-api          1 hr 49 mins        ████████░░░░░░░░░░░░░░░░░   35.36% 
air-codes                49 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.18% 
quatro                   15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.98% 
baba-mandef              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26%

💻 Operating System: 
Linux                    5 hrs 8 mins        █████████████████████████   100.0%

```


 Last Updated on 22/09/2023 18:34:20 UTC
<!--END_SECTION:waka-->
