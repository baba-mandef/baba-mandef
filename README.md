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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C141%20hrs%2044%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     8 hrs 34 mins       █████████████████░░░░░░░░   71.39% 
Python                   2 hrs 28 mins       █████░░░░░░░░░░░░░░░░░░░░   20.58% 
CSS                      33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.61% 
Text                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.17% 
Markdown                 5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74%

🔥 Editors: 
VS Code                  12 hrs              █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    12 hrs              █████████████████████████   100.0%

💻 Operating System: 
Linux                    12 hrs              █████████████████████████   100.0%

```


 Last Updated on 15/09/2024 18:46:40 UTC
<!--END_SECTION:waka-->
