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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C009%20hrs%2034%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-275%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     7 hrs 19 mins       █████████████████████░░░░   84.71% 
JavaScript               42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.17% 
CSS                      21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.17% 
Python                   15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.95%

🔥 Editors: 
VS Code                  8 hrs 39 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
omotunde-mural           8 hrs 39 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    8 hrs 39 mins       █████████████████████████   100.0%

```


 Last Updated on 11/04/2024 18:38:03 UTC
<!--END_SECTION:waka-->
