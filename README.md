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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C024%20hrs%2043%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-255%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               8 hrs 1 min         ██████████████░░░░░░░░░░░   57.28% 
CSS                      3 hrs 38 mins       ██████░░░░░░░░░░░░░░░░░░░   26.02% 
JSON                     53 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.39% 
SCSS                     48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.79% 
HTML                     37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.47%

🔥 Editors: 
VS Code                  14 hrs              █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              14 hrs              █████████████████████████   100.0%

💻 Operating System: 
Linux                    14 hrs              █████████████████████████   100.0%

```


 Last Updated on 29/04/2024 18:43:06 UTC
<!--END_SECTION:waka-->
