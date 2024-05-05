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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C038%20hrs%2023%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-255%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               13 hrs 57 mins      ███████████████████░░░░░░   78.08% 
CSS                      2 hrs 35 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.54% 
Text                     46 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.34% 
SCSS                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.08% 
HTML                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56%

🔥 Editors: 
VS Code                  17 hrs 52 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              17 hrs 52 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    17 hrs 52 mins      █████████████████████████   100.0%

```


 Last Updated on 05/05/2024 18:39:13 UTC
<!--END_SECTION:waka-->
