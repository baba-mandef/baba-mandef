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
![Code Time](http://img.shields.io/badge/Code%20Time-890%20hrs%2026%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

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
Python                   8 hrs 58 mins       █████████████░░░░░░░░░░░░   55.08% 
HTML                     5 hrs 42 mins       ████████░░░░░░░░░░░░░░░░░   35.06% 
JavaScript               1 hr                █░░░░░░░░░░░░░░░░░░░░░░░░   6.22% 
Text                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.31% 
CSS                      12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.25%

🔥 Editors: 
VS Code                  16 hrs 17 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
sub                      14 hrs 19 mins      ██████████████████████░░░   87.91% 
lavy                     1 hr 20 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.27% 
template_01              21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22% 
baba-mandef-api          15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.6%

💻 Operating System: 
Linux                    16 hrs 17 mins      █████████████████████████   100.0%

```


 Last Updated on 23/11/2023 18:34:16 UTC
<!--END_SECTION:waka-->
