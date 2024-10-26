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
                       'languages': ['Python', 'JS', 'Dart'],
                       'tools': ['Django', 'React', 'Flutter'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['Web developer', 'Content Creator', 'Teacher', 'Mentor'],
            'AskMe': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C182%20hrs%2027%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     6 hrs 39 mins       ████████████░░░░░░░░░░░░░   49.13% 
Python                   6 hrs 12 mins       ███████████░░░░░░░░░░░░░░   45.82% 
JavaScript               25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.18% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.87% 
Text                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.65%

🔥 Editors: 
VS Code                  13 hrs 33 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 12 hrs 47 mins      ███████████████████████░░   94.28% 
omural                   37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.57% 
back-end                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77% 
api.abiodoun.dev         3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.38%

💻 Operating System: 
Linux                    13 hrs 33 mins      █████████████████████████   100.0%

```


 Last Updated on 26/10/2024 18:47:41 UTC
<!--END_SECTION:waka-->
