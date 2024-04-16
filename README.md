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
HTML                     2 hrs 46 mins       ██████████████████░░░░░░░   74.74% 
Dart                     41 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.82% 
JavaScript               10 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.91% 
XML                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.51% 
CSS                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.45%

🔥 Editors: 
VS Code                  3 hrs 42 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
omotunde-mural           2 hrs 58 mins       ████████████████████░░░░░   80.28% 
ishiro                   43 mins             █████░░░░░░░░░░░░░░░░░░░░   19.72%

💻 Operating System: 
Linux                    3 hrs 42 mins       █████████████████████████   100.0%

```


 Last Updated on 16/04/2024 18:38:25 UTC
<!--END_SECTION:waka-->
