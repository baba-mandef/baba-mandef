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
![Code Time](http://img.shields.io/badge/Code%20Time-893%20hrs%2048%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 602 Contributions in the Year 2023
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
Python                   2 hrs 40 mins       ███████████████░░░░░░░░░░   59.53% 
HTML                     1 hr 21 mins        ███████░░░░░░░░░░░░░░░░░░   30.07% 
Text                     17 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.51% 
JavaScript               9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.37% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44%

🔥 Editors: 
VS Code                  4 hrs 30 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
lavy                     4 hrs 29 mins       █████████████████████████   99.91% 
sub                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

💻 Operating System: 
Linux                    4 hrs 30 mins       █████████████████████████   100.0%

```


 Last Updated on 29/11/2023 18:33:42 UTC
<!--END_SECTION:waka-->
