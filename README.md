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
![Code Time](http://img.shields.io/badge/Code%20Time-806%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

**🐱 My GitHub Data** 

> 🏆 581 Contributions in the Year 2023
 > 
> 📦 98.6 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 41 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   3 hrs 42 mins       ████████████░░░░░░░░░░░░░   48.13% 
HTML                     3 hrs 37 mins       ███████████░░░░░░░░░░░░░░   47.25% 
CSS                      15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.45% 
JavaScript               5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.17%

🔥 Editors: 
VS Code                  6 hrs 41 mins       █████████████████████░░░░   87.1% 
PyCharmCore              59 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.9%

🐱‍💻 Projects: 
sub                      6 hrs 15 mins       ████████████████████░░░░░   81.44% 
quatro                   1 hr 13 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.89% 
default                  12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.67%

💻 Operating System: 
Linux                    7 hrs 41 mins       █████████████████████████   100.0%

```


 Last Updated on 26/10/2023 18:34:25 UTC
<!--END_SECTION:waka-->
