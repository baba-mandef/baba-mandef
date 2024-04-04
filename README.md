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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C001%20hrs%2019%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-275%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     2 hrs 33 mins       █████████░░░░░░░░░░░░░░░░   38.35% 
Python                   1 hr 42 mins        ██████░░░░░░░░░░░░░░░░░░░   25.63% 
HTML                     1 hr 41 mins        ██████░░░░░░░░░░░░░░░░░░░   25.33% 
CSS                      29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.38% 
SCSS                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.55%

🔥 Editors: 
VS Code                  6 hrs 41 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
omotunde-mural           2 hrs 38 mins       █████████░░░░░░░░░░░░░░░░   39.38% 
ishiro                   2 hrs 33 mins       █████████░░░░░░░░░░░░░░░░   38.35% 
api.abiodoun.dev         1 hr 7 mins         ████░░░░░░░░░░░░░░░░░░░░░   16.83% 
henri-front              13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.24% 
Keystroke                8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.2%

💻 Operating System: 
Linux                    6 hrs 41 mins       █████████████████████████   100.0%

```


 Last Updated on 04/04/2024 18:40:26 UTC
<!--END_SECTION:waka-->
