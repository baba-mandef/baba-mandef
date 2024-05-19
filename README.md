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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C070%20hrs%203%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               12 hrs 2 mins       ████████████████░░░░░░░░░   66.07% 
CSS                      3 hrs 35 mins       █████░░░░░░░░░░░░░░░░░░░░   19.67% 
SCSS                     57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.24% 
JSON                     42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.9% 
Python                   24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.28%

🔥 Editors: 
VS Code                  18 hrs 13 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              14 hrs 11 mins      ███████████████████░░░░░░   77.83% 
rezolusoft.com           3 hrs 34 mins       █████░░░░░░░░░░░░░░░░░░░░   19.59% 
api.etalents.com         23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.18% 
Zenfy                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.22% 
api.korbo.fr             1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

💻 Operating System: 
Linux                    18 hrs 13 mins      █████████████████████████   100.0%

```


 Last Updated on 19/05/2024 18:38:50 UTC
<!--END_SECTION:waka-->
