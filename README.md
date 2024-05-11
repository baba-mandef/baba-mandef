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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C049%20hrs%2038%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               9 hrs               ███████████████████░░░░░░   75.56% 
Text                     1 hr 18 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.98% 
CSS                      47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.7% 
HTML                     34 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.85% 
JSON                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.52%

🔥 Editors: 
VS Code                  11 hrs 55 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
etalents.com             6 hrs 46 mins       ██████████████░░░░░░░░░░░   56.8% 
kreativ.inc              4 hrs 56 mins       ██████████░░░░░░░░░░░░░░░   41.46% 
tabler                   12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.74%

💻 Operating System: 
Linux                    11 hrs 55 mins      █████████████████████████   100.0%

```


 Last Updated on 11/05/2024 18:39:20 UTC
<!--END_SECTION:waka-->
