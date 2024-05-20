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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C070%20hrs%2032%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               11 hrs 19 mins      ████████████████░░░░░░░░░   65.87% 
CSS                      2 hrs 57 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.23% 
SCSS                     1 hr 15 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.34% 
JSON                     42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.13% 
Python                   24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.42%

🔥 Editors: 
VS Code                  17 hrs 11 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              12 hrs 27 mins      ██████████████████░░░░░░░   72.43% 
rezolusoft.com           4 hrs 16 mins       ██████░░░░░░░░░░░░░░░░░░░   24.83% 
api.etalents.com         23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.31% 
Zenfy                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23% 
api.korbo.fr             1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

💻 Operating System: 
Linux                    17 hrs 11 mins      █████████████████████████   100.0%

```


 Last Updated on 20/05/2024 18:42:04 UTC
<!--END_SECTION:waka-->
