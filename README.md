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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C013%20hrs%207%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-275%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     2 hrs 1 min         ████████████████████████░   96.96% 
YAML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.44% 
XML                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.91% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.68% 
Python                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
VS Code                  2 hrs 5 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   2 hrs 5 mins        █████████████████████████   99.99% 
api.ishiro.com           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    2 hrs 5 mins        █████████████████████████   100.0%

```


 Last Updated on 19/04/2024 18:38:18 UTC
<!--END_SECTION:waka-->
