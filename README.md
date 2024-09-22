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
HTML                     5 hrs 50 mins       ██████████████████░░░░░░░   72.86% 
Python                   1 hr 27 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.23% 
CSS                      38 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.05% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.78% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  8 hrs               █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    7 hrs 55 mins       ████████████████████████░   99.02% 
omural                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.98%

💻 Operating System: 
Linux                    8 hrs               █████████████████████████   100.0%

```


 Last Updated on 22/09/2024 18:48:29 UTC
<!--END_SECTION:waka-->
