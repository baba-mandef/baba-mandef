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
![Code Time](http://img.shields.io/badge/Code%20Time-789%20hrs%2036%20mins-blue)

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
Python                   7 hrs 53 mins       ███████████████████████░░   93.06% 
Bash                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.57% 
GDScript                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.32% 
YAML                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.23% 
Markdown                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89%

🔥 Editors: 
VS Code                  8 hrs 16 mins       ████████████████████████░   97.63% 
PyCharmCore              12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.37%

🐱‍💻 Projects: 
iwedioro                 4 hrs 12 mins       ████████████░░░░░░░░░░░░░   49.73% 
quatro                   3 hrs 4 mins        █████████░░░░░░░░░░░░░░░░   36.3% 
kareeba                  55 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.88% 
django-zoho-mail         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.25% 
travel-service-api       4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84%

💻 Operating System: 
Linux                    8 hrs 28 mins       █████████████████████████   100.0%

```


 Last Updated on 08/10/2023 18:33:52 UTC
<!--END_SECTION:waka-->
