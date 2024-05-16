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
JavaScript               10 hrs 51 mins      ███████████████░░░░░░░░░░   63.04% 
CSS                      5 hrs 8 mins        ███████░░░░░░░░░░░░░░░░░░   29.84% 
SCSS                     39 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.79% 
Text                     30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.95% 
HTML                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.22%

🔥 Editors: 
VS Code                  17 hrs 13 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              16 hrs 47 mins      ████████████████████████░   97.51% 
etalents.com             23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.25% 
Zenfy                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23%

💻 Operating System: 
Linux                    17 hrs 13 mins      █████████████████████████   100.0%

```


 Last Updated on 16/05/2024 18:40:40 UTC
<!--END_SECTION:waka-->
