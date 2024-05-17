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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C066%20hrs%2028%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               10 hrs 55 mins      ████████████████░░░░░░░░░   64.15% 
CSS                      5 hrs 8 mins        ███████░░░░░░░░░░░░░░░░░░   30.16% 
SCSS                     39 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.83% 
Python                   7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77% 
Text                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.7%

🔥 Editors: 
VS Code                  17 hrs 2 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              16 hrs 52 mins      ████████████████████████░   98.99% 
api.etalents.com         7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74% 
Zenfy                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23% 
api.korbo.fr             0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

💻 Operating System: 
Linux                    17 hrs 2 mins       █████████████████████████   100.0%

```


 Last Updated on 17/05/2024 18:41:43 UTC
<!--END_SECTION:waka-->
