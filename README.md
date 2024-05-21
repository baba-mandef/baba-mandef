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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C071%20hrs%2014%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               7 hrs 22 mins       ███████████████░░░░░░░░░░   63.4% 
CSS                      1 hr 59 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.1% 
SCSS                     44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.34% 
JSON                     42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.11% 
Python                   24 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.58%

🔥 Editors: 
VS Code                  11 hrs 37 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              6 hrs 52 mins       ██████████████░░░░░░░░░░░   59.22% 
rezolusoft.com           4 hrs 16 mins       █████████░░░░░░░░░░░░░░░░   36.73% 
api.etalents.com         23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.42% 
Zenfy                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34% 
api.korbo.fr             1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28%

💻 Operating System: 
Linux                    11 hrs 37 mins      █████████████████████████   100.0%

```


 Last Updated on 21/05/2024 18:40:47 UTC
<!--END_SECTION:waka-->
