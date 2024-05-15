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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C059%20hrs%2037%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               14 hrs 48 mins      ████████████████░░░░░░░░░   67.06% 
CSS                      5 hrs 8 mins        █████░░░░░░░░░░░░░░░░░░░░   23.26% 
Text                     1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.85% 
SCSS                     39 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.95% 
HTML                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74%

🔥 Editors: 
VS Code                  22 hrs 5 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              16 hrs 47 mins      ███████████████████░░░░░░   76.01% 
etalents.com             5 hrs 7 mins        █████░░░░░░░░░░░░░░░░░░░░   23.23% 
tabler                   7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57% 
Zenfy                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

💻 Operating System: 
Linux                    22 hrs 5 mins       █████████████████████████   100.0%

```


 Last Updated on 15/05/2024 18:41:48 UTC
<!--END_SECTION:waka-->
