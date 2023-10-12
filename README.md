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
![Code Time](http://img.shields.io/badge/Code%20Time-789%20hrs%2053%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 580 Contributions in the Year 2023
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
Python                   56 mins             ███████████████████░░░░░░   79.18% 
GDScript                 6 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   9.42% 
YAML                     5 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   7.32% 
TOML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   2.57% 
Bash                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.46%

🔥 Editors: 
VS Code                  59 mins             ████████████████████░░░░░   83.04% 
PyCharmCore              12 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.96%

🐱‍💻 Projects: 
quatro                   40 mins             ██████████████░░░░░░░░░░░   56.88% 
kareeba                  19 mins             ██████░░░░░░░░░░░░░░░░░░░   27.07% 
django-zoho-mail         11 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.06%

💻 Operating System: 
Linux                    1 hr 11 mins        █████████████████████████   100.0%

```


 Last Updated on 12/10/2023 18:35:53 UTC
<!--END_SECTION:waka-->
