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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C073%20hrs%2057%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-437%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               2 hrs 58 mins       ██████████████████░░░░░░░   72.34% 
HTML                     48 mins             █████░░░░░░░░░░░░░░░░░░░░   19.5% 
CSS                      15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.23% 
Other                    4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.78% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  4 hrs 7 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
omural                   4 hrs 6 mins        █████████████████████████   99.6% 
omotunde-mural           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.4%

💻 Operating System: 
Linux                    4 hrs 7 mins        █████████████████████████   100.0%

```


 Last Updated on 06/06/2024 18:41:53 UTC
<!--END_SECTION:waka-->
