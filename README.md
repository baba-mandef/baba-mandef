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
                       'languages': ['Python', 'Php', 'JS', 'Dart'],
                       'tools': ['Django', 'Nuxt2', 'React', 'NextJS', 'Flutter'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['freelance web and mobile developer', 'Content creator', 'Teacher', 'Mentor'],
            'AskMe': ['DIY', 'Food', 'Africa', 'Science', 'Comics', 'Photography', 'Tech', 'Programming', 'Mechatronics'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C042%20hrs%2035%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-255%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               12 hrs 14 mins      ███████████████████░░░░░░   79.24% 
CSS                      2 hrs 4 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.47% 
Text                     46 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.02% 
SCSS                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.12% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

🔥 Editors: 
VS Code                  15 hrs 27 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              15 hrs 27 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    15 hrs 27 mins      █████████████████████████   100.0%

```


 Last Updated on 06/05/2024 18:42:48 UTC
<!--END_SECTION:waka-->
