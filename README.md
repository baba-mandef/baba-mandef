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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C011%20hrs%2045%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-275%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     2 hrs 1 min         ██████████████░░░░░░░░░░░   57.21% 
HTML                     1 hr 26 mins        ██████████░░░░░░░░░░░░░░░   40.45% 
YAML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.85% 
XML                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.54% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.4%

🔥 Editors: 
VS Code                  3 hrs 33 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   2 hrs 5 mins        ██████████████░░░░░░░░░░░   59.0% 
omotunde-mural           1 hr 27 mins        ██████████░░░░░░░░░░░░░░░   40.99% 
api.ishiro.com           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

💻 Operating System: 
Linux                    3 hrs 33 mins       █████████████████████████   100.0%

```


 Last Updated on 17/04/2024 18:39:17 UTC
<!--END_SECTION:waka-->
