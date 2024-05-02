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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C032%20hrs%2039%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-255%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               14 hrs 15 mins      ███████████████░░░░░░░░░░   63.39% 
CSS                      5 hrs 17 mins       ██████░░░░░░░░░░░░░░░░░░░   23.54% 
SCSS                     1 hr 8 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.06% 
Text                     41 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.07% 
HTML                     36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.68%

🔥 Editors: 
VS Code                  22 hrs 29 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              22 hrs 29 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    22 hrs 29 mins      █████████████████████████   100.0%

```


 Last Updated on 02/05/2024 18:40:07 UTC
<!--END_SECTION:waka-->
