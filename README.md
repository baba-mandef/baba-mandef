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
![Code Time](http://img.shields.io/badge/Code%20Time-758%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 514 Contributions in the Year 2023
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
Python                   8 hrs 36 mins       ████████████████████░░░░░   82.6% 
Nginx configuration file 33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.37% 
YAML                     29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.78% 
Dart                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.88% 
XML                      8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.39%

🔥 Editors: 
PyCharmCore              9 hrs 43 mins       ███████████████████████░░   93.39% 
Android Studio           29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.74% 
VS Code                  11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.87%

🐱‍💻 Projects: 
quatro                   8 hrs 4 mins        ███████████████████░░░░░░   77.6% 
baba-mandef-api          1 hr 50 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.65% 
dema                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.28% 
course                   8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.3% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.15%

💻 Operating System: 
Linux                    10 hrs 24 mins      █████████████████████████   100.0%

```


 Last Updated on 07/09/2023 18:34:53 UTC
<!--END_SECTION:waka-->
