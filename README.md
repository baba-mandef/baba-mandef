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
                       'tools': ['Django', 'VueJS', 'React', 'Jetpack Compose'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-903%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-4-blue)

**🐱 My GitHub Data** 

> 🏆 3 Contributions in the Year 2024
 > 
> 📦 36.8 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 12 Public Repositories 
 > 
> 🔑 2 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
YAML                     24 mins             █████████████░░░░░░░░░░░░   52.52% 
Python                   12 mins             ██████░░░░░░░░░░░░░░░░░░░   25.3% 
Bash                     5 mins              ███░░░░░░░░░░░░░░░░░░░░░░   12.43% 
Nginx configuration file 2 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.13% 
Git Config               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.82%

🔥 Editors: 
VS Code                  47 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
lavy                     28 mins             ██████████████░░░░░░░░░░░   59.42% 
api.abiodoun.dev         19 mins             ██████████░░░░░░░░░░░░░░░   40.58%

💻 Operating System: 
Linux                    47 mins             █████████████████████████   100.0%

```


 Last Updated on 21/01/2024 18:34:41 UTC
<!--END_SECTION:waka-->
