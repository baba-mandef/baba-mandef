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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C052%20hrs%2019%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               7 hrs 2 mins        ███████████████░░░░░░░░░░   61.39% 
CSS                      2 hrs 20 mins       █████░░░░░░░░░░░░░░░░░░░░   20.45% 
Text                     1 hr 13 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.75% 
HTML                     35 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.17% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.82%

🔥 Editors: 
VS Code                  11 hrs 28 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
etalents.com             6 hrs 46 mins       ██████████████░░░░░░░░░░░   59.1% 
kreativ.inc              4 hrs 29 mins       █████████░░░░░░░░░░░░░░░░   39.09% 
tabler                   12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.81%

💻 Operating System: 
Linux                    11 hrs 28 mins      █████████████████████████   100.0%

```


 Last Updated on 13/05/2024 18:40:49 UTC
<!--END_SECTION:waka-->
