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
![Code Time](http://img.shields.io/badge/Code%20Time-875%20hrs%2029%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

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
HTML                     14 hrs 13 mins      ███████████████░░░░░░░░░░   60.76% 
Python                   7 hrs 31 mins       ████████░░░░░░░░░░░░░░░░░   32.15% 
JavaScript               50 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.63% 
CSS                      31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.27% 
SCSS                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.67%

🔥 Editors: 
VS Code                  23 hrs 25 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      13 hrs 43 mins      ██████████████░░░░░░░░░░░   58.57% 
template_01              9 hrs 26 mins       ██████████░░░░░░░░░░░░░░░   40.32% 
baba-mandef-api          15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12%

💻 Operating System: 
Linux                    23 hrs 25 mins      █████████████████████████   100.0%

```


 Last Updated on 21/11/2023 18:36:52 UTC
<!--END_SECTION:waka-->
