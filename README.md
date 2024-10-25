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
HTML                     7 hrs 32 mins       ████████████░░░░░░░░░░░░░   49.62% 
Python                   6 hrs 57 mins       ███████████░░░░░░░░░░░░░░   45.76% 
JavaScript               27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.02% 
CSS                      6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.72% 
Text                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.58%

🔥 Editors: 
VS Code                  15 hrs 12 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 15 hrs 3 mins       ████████████████████████░   98.97% 
back-end                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.69% 
api.abiodoun.dev         3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34%

💻 Operating System: 
Linux                    15 hrs 12 mins      █████████████████████████   100.0%

```


 Last Updated on 25/10/2024 18:50:23 UTC
<!--END_SECTION:waka-->
