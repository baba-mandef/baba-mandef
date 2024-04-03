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
![Code Time](http://img.shields.io/badge/Code%20Time-998%20hrs%206%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-275%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     5 hrs 33 mins       ████████████████░░░░░░░░░   64.34% 
Python                   1 hr 37 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.78% 
HTML                     1 hr 2 mins         ███░░░░░░░░░░░░░░░░░░░░░░   11.98% 
CSS                      12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.34% 
SCSS                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.98%

🔥 Editors: 
VS Code                  8 hrs 38 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   5 hrs 33 mins       ████████████████░░░░░░░░░   64.33% 
omotunde-mural           1 hr 35 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.4% 
api.abiodoun.dev         1 hr 7 mins         ███░░░░░░░░░░░░░░░░░░░░░░   13.04% 
henri-front              13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.51% 
Keystroke                8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.7%

💻 Operating System: 
Linux                    8 hrs 38 mins       █████████████████████████   100.0%

```


 Last Updated on 03/04/2024 18:39:02 UTC
<!--END_SECTION:waka-->
