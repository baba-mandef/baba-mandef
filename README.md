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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C004%20hrs%2046%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-275%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     3 hrs 50 mins       ███████████░░░░░░░░░░░░░░   47.33% 
Dart                     1 hr 58 mins        ██████░░░░░░░░░░░░░░░░░░░   24.31% 
Python                   1 hr 53 mins        █████░░░░░░░░░░░░░░░░░░░░   23.3% 
CSS                      24 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.96% 
YAML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  8 hrs 7 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
omotunde-mural           5 hrs 1 min         ███████████████░░░░░░░░░░   61.84% 
ishiro                   1 hr 58 mins        ██████░░░░░░░░░░░░░░░░░░░   24.31% 
api.abiodoun.dev         1 hr 7 mins         ███░░░░░░░░░░░░░░░░░░░░░░   13.85%

💻 Operating System: 
Linux                    8 hrs 7 mins        █████████████████████████   100.0%

```


 Last Updated on 06/04/2024 18:42:32 UTC
<!--END_SECTION:waka-->
