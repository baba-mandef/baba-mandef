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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C082%20hrs%2054%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   5 hrs 30 mins       ███████████████████████░░   94.03% 
Bash                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.45% 
Text                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.33% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.09% 
HTML                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.76%

🔥 Editors: 
VS Code                  5 hrs 51 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
api.korbo.fr             5 hrs 44 mins       ████████████████████████░   98.05% 
olanike                  4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.37% 
drf-redesign             2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.58%

💻 Operating System: 
Linux                    5 hrs 51 mins       █████████████████████████   100.0%

```


 Last Updated on 14/06/2024 18:45:52 UTC
<!--END_SECTION:waka-->
