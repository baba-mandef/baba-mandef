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
![Code Time](http://img.shields.io/badge/Code%20Time-902%20hrs%202%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 604 Contributions in the Year 2023
 > 
> 📦 98.7 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 42 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   5 mins              █████████░░░░░░░░░░░░░░░░   38.42% 
JavaScript               3 mins              ███████░░░░░░░░░░░░░░░░░░   28.81% 
Markdown                 2 mins              ████░░░░░░░░░░░░░░░░░░░░░   17.78% 
HTML                     1 min               ██░░░░░░░░░░░░░░░░░░░░░░░   9.5% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.31%

🔥 Editors: 
VS Code                  13 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
home.korbo.fr            13 mins             █████████████████████████   100.0%

💻 Operating System: 
Linux                    13 mins             █████████████████████████   100.0%

```


 Last Updated on 22/12/2023 18:33:46 UTC
<!--END_SECTION:waka-->
