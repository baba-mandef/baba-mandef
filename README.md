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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C150%20hrs%2017%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     6 hrs 25 mins       ██████████████████░░░░░░░   74.16% 
Python                   1 hr 31 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.58% 
CSS                      38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.47% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.73% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  8 hrs 39 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    8 hrs 34 mins       ████████████████████████░   99.1% 
omural                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.9%

💻 Operating System: 
Linux                    8 hrs 39 mins       █████████████████████████   100.0%

```


 Last Updated on 20/09/2024 18:47:26 UTC
<!--END_SECTION:waka-->
