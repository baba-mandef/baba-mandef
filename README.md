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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C011%20hrs%201%20min-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-275%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     5 hrs 9 mins        ████████████████████░░░░░   82.4% 
JavaScript               42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.23% 
CSS                      19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.16% 
Python                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.21%

🔥 Editors: 
VS Code                  6 hrs 15 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
omotunde-mural           6 hrs 15 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    6 hrs 15 mins       █████████████████████████   100.0%

```


 Last Updated on 12/04/2024 18:38:24 UTC
<!--END_SECTION:waka-->
