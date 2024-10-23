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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C182%20hrs%2022%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     9 hrs 33 mins       █████████████░░░░░░░░░░░░   51.74% 
Python                   8 hrs 11 mins       ███████████░░░░░░░░░░░░░░   44.38% 
JavaScript               27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.48% 
CSS                      6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.59% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.55%

🔥 Editors: 
VS Code                  18 hrs 28 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 18 hrs 18 mins      ████████████████████████░   99.15% 
back-end                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57% 
api.abiodoun.dev         3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28%

💻 Operating System: 
Linux                    18 hrs 28 mins      █████████████████████████   100.0%

```


 Last Updated on 23/10/2024 18:48:18 UTC
<!--END_SECTION:waka-->
