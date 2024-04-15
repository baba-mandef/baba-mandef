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
HTML                     3 hrs 41 mins       █████████████████░░░░░░░░   69.14% 
JavaScript               42 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.17% 
Dart                     41 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.06% 
CSS                      11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.64% 
Python                   1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36%

🔥 Editors: 
VS Code                  5 hrs 20 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
omotunde-mural           4 hrs 36 mins       █████████████████████░░░░   86.31% 
ishiro                   43 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.69%

💻 Operating System: 
Linux                    5 hrs 20 mins       █████████████████████████   100.0%

```


 Last Updated on 15/04/2024 18:40:01 UTC
<!--END_SECTION:waka-->
