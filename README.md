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
![Code Time](http://img.shields.io/badge/Code%20Time-997%20hrs%2045%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-270%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     4 hrs 4 mins        ██████████████████░░░░░░░   73.22% 
Python                   1 hr 7 mins         █████░░░░░░░░░░░░░░░░░░░░   20.16% 
SCSS                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.07% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.31% 
Vue.js                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.83%

🔥 Editors: 
VS Code                  5 hrs 33 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   4 hrs 4 mins        ██████████████████░░░░░░░   73.2% 
api.abiodoun.dev         1 hr 7 mins         █████░░░░░░░░░░░░░░░░░░░░   20.24% 
henri-front              13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.9% 
Keystroke                8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.64% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

💻 Operating System: 
Linux                    5 hrs 33 mins       █████████████████████████   100.0%

```


 Last Updated on 02/04/2024 18:39:10 UTC
<!--END_SECTION:waka-->
