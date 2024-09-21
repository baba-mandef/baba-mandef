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
HTML                     6 hrs 19 mins       ██████████████████░░░░░░░   73.86% 
Python                   1 hr 31 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.78% 
CSS                      38 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.56% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.73% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  8 hrs 33 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    8 hrs 28 mins       ████████████████████████░   99.09% 
omural                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.91%

💻 Operating System: 
Linux                    8 hrs 33 mins       █████████████████████████   100.0%

```


 Last Updated on 21/09/2024 18:45:17 UTC
<!--END_SECTION:waka-->
