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
Python                   46 mins             █████████████████░░░░░░░░   67.8% 
Nginx configuration file 20 mins             ███████░░░░░░░░░░░░░░░░░░   29.54% 
YAML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.49% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.17%

🔥 Editors: 
VS Code                  51 mins             ███████████████████░░░░░░   76.17% 
PyCharmCore              16 mins             ██████░░░░░░░░░░░░░░░░░░░   23.83%

🐱‍💻 Projects: 
travel-service-api       45 mins             ████████████████░░░░░░░░░   66.36% 
baba-mandef-api          21 mins             ███████░░░░░░░░░░░░░░░░░░   31.03% 
quatro                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.43% 
baba-mandef              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.17%

💻 Operating System: 
Linux                    1 hr 8 mins         █████████████████████████   100.0%

```


 Last Updated on 28/09/2023 18:34:35 UTC
<!--END_SECTION:waka-->
