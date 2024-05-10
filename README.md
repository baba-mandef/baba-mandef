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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C049%20hrs%2015%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               10 hrs 47 mins      ████████████████████░░░░░   80.35% 
Text                     1 hr 19 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.82% 
HTML                     34 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.25% 
CSS                      31 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.88% 
JSON                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.35%

🔥 Editors: 
VS Code                  13 hrs 25 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
etalents.com             6 hrs 46 mins       ████████████░░░░░░░░░░░░░   50.47% 
kreativ.inc              6 hrs 26 mins       ████████████░░░░░░░░░░░░░   47.99% 
tabler                   12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55%

💻 Operating System: 
Linux                    13 hrs 25 mins      █████████████████████████   100.0%

```


 Last Updated on 10/05/2024 18:40:35 UTC
<!--END_SECTION:waka-->
