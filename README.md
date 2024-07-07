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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C101%20hrs%2049%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               5 hrs 14 mins       ███████████████████████░░   92.48% 
CSS                      13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.86% 
HTML                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.07% 
JSON                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.49% 
Markdown                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

🔥 Editors: 
VS Code                  5 hrs 40 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           5 hrs 37 mins       ████████████████████████░   99.13% 
omural                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.87%

💻 Operating System: 
Linux                    5 hrs 40 mins       █████████████████████████   100.0%

```


 Last Updated on 07/07/2024 18:40:49 UTC
<!--END_SECTION:waka-->
