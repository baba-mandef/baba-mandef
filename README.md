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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C130%20hrs%2045%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     1 hr 59 mins        ███████████░░░░░░░░░░░░░░   46.64% 
Python                   1 hr 36 mins        █████████░░░░░░░░░░░░░░░░   37.7% 
CSS                      15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.18% 
Text                     15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.11% 
Markdown                 5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.07%

🔥 Editors: 
VS Code                  4 hrs 15 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    4 hrs 15 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    4 hrs 15 mins       █████████████████████████   100.0%

```


 Last Updated on 12/09/2024 18:47:31 UTC
<!--END_SECTION:waka-->
