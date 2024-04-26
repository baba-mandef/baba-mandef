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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C013%20hrs%2042%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-275%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               1 hr 28 mins        █████████░░░░░░░░░░░░░░░░   35.92% 
JSON                     48 mins             █████░░░░░░░░░░░░░░░░░░░░   19.68% 
CSS                      45 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.54% 
SCSS                     37 mins             ███░░░░░░░░░░░░░░░░░░░░░░   15.03% 
HTML                     26 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.72%

🔥 Editors: 
VS Code                  4 hrs 7 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              4 hrs 7 mins        █████████████████████████   100.0%

💻 Operating System: 
Linux                    4 hrs 7 mins        █████████████████████████   100.0%

```


 Last Updated on 26/04/2024 18:39:08 UTC
<!--END_SECTION:waka-->
