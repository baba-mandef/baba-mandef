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
![Code Time](http://img.shields.io/badge/Code%20Time-805%20hrs%2031%20mins-blue)

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
HTML                     6 hrs 1 min         ██████████████░░░░░░░░░░░   58.03% 
Python                   3 hrs 52 mins       █████████░░░░░░░░░░░░░░░░   37.37% 
CSS                      23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.73% 
JavaScript               5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.86% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
VS Code                  9 hrs 23 mins       ██████████████████████░░░   90.44% 
PyCharmCore              59 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.56%

🐱‍💻 Projects: 
sub                      8 hrs 46 mins       █████████████████████░░░░   84.59% 
quatro                   1 hr 12 mins        ███░░░░░░░░░░░░░░░░░░░░░░   11.71% 
default                  23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.71%

💻 Operating System: 
Linux                    10 hrs 22 mins      █████████████████████████   100.0%

```


 Last Updated on 24/10/2023 18:35:31 UTC
<!--END_SECTION:waka-->
