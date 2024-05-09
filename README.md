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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C044%20hrs%2022%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               10 hrs 47 mins      ████████████████████░░░░░   82.75% 
Text                     55 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.13% 
HTML                     34 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.37% 
CSS                      31 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.0% 
JSON                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.39%

🔥 Editors: 
VS Code                  13 hrs 2 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              6 hrs 27 mins       ████████████░░░░░░░░░░░░░   49.44% 
etalents.com             6 hrs 23 mins       ████████████░░░░░░░░░░░░░   48.97% 
tabler                   12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.59%

💻 Operating System: 
Linux                    13 hrs 2 mins       █████████████████████████   100.0%

```


 Last Updated on 09/05/2024 18:39:43 UTC
<!--END_SECTION:waka-->
