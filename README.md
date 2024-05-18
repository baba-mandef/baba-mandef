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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C066%20hrs%2040%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               12 hrs 32 mins      ████████████████░░░░░░░░░   63.54% 
CSS                      4 hrs 33 mins       █████░░░░░░░░░░░░░░░░░░░░   23.08% 
SCSS                     57 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.84% 
JSON                     44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.74% 
Python                   24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.11%

🔥 Editors: 
VS Code                  19 hrs 44 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              16 hrs 11 mins      ████████████████████░░░░░   82.01% 
rezolusoft.com           3 hrs 4 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.6% 
api.etalents.com         23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.01% 
Zenfy                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2% 
api.korbo.fr             1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

💻 Operating System: 
Linux                    19 hrs 44 mins      █████████████████████████   100.0%

```


 Last Updated on 18/05/2024 18:39:03 UTC
<!--END_SECTION:waka-->
