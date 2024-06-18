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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C084%20hrs%201%20min-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   6 hrs 34 mins       ███████████████████████░░   94.95% 
Bash                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.07% 
Text                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.92% 
HTML                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.64%

🔥 Editors: 
VS Code                  6 hrs 55 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
api.korbo.fr             6 hrs 48 mins       ████████████████████████░   98.35% 
olanike                  4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.16% 
drf-redesign             2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.49%

💻 Operating System: 
Linux                    6 hrs 55 mins       █████████████████████████   100.0%

```


 Last Updated on 18/06/2024 18:44:42 UTC
<!--END_SECTION:waka-->
