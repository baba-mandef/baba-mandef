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
![Code Time](http://img.shields.io/badge/Code%20Time-768%20hrs%201%20min-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 534 Contributions in the Year 2023
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
Python                   4 hrs 4 mins        ███████████████░░░░░░░░░░   60.91% 
YAML                     1 hr 29 mins        █████░░░░░░░░░░░░░░░░░░░░   22.29% 
Nginx configuration file 20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.12% 
XML                      18 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.52% 
Nginx Configuration      14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.64%

🔥 Editors: 
PyCharmCore              6 hrs 31 mins       ████████████████████████░   97.49% 
VS Code                  10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.51%

🐱‍💻 Projects: 
baba-mandef-api          3 hrs 9 mins        ███████████░░░░░░░░░░░░░░   47.2% 
quatro                   2 hrs 18 mins       ████████░░░░░░░░░░░░░░░░░   34.4% 
travel-service-api       1 hr 13 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.4%

💻 Operating System: 
Linux                    6 hrs 42 mins       █████████████████████████   100.0%

```


 Last Updated on 14/09/2023 18:33:53 UTC
<!--END_SECTION:waka-->
