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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C050%20hrs%2019%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               5 hrs 58 mins       ███████████████░░░░░░░░░░   61.46% 
CSS                      1 hr 40 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.17% 
Text                     1 hr 13 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.67% 
HTML                     35 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.07% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.14%

🔥 Editors: 
VS Code                  9 hrs 43 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
etalents.com             6 hrs 46 mins       █████████████████░░░░░░░░   69.64% 
kreativ.inc              2 hrs 44 mins       ███████░░░░░░░░░░░░░░░░░░   28.22% 
tabler                   12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.13%

💻 Operating System: 
Linux                    9 hrs 43 mins       █████████████████████████   100.0%

```


 Last Updated on 12/05/2024 18:39:58 UTC
<!--END_SECTION:waka-->
