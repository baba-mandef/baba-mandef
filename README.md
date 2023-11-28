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
![Code Time](http://img.shields.io/badge/Code%20Time-891%20hrs%2047%20mins-blue)

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
Python                   2 hrs 44 mins       ██████████████████░░░░░░░   74.6% 
HTML                     29 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.19% 
Text                     17 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.98% 
JavaScript               9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.13% 
Git                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

🔥 Editors: 
VS Code                  3 hrs 40 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
lavy                     3 hrs 22 mins       ███████████████████████░░   91.74% 
sub                      18 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.26%

💻 Operating System: 
Linux                    3 hrs 40 mins       █████████████████████████   100.0%

```


 Last Updated on 28/11/2023 18:35:27 UTC
<!--END_SECTION:waka-->
