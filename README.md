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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C147%20hrs%202%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     14 hrs 24 mins      ██████████████████░░░░░░░   73.8% 
Python                   3 hrs 26 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.6% 
CSS                      1 hr 11 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.14% 
Text                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.66% 
Markdown                 5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.45%

🔥 Editors: 
VS Code                  19 hrs 31 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    19 hrs 26 mins      █████████████████████████   99.6% 
omural                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.4%

💻 Operating System: 
Linux                    19 hrs 31 mins      █████████████████████████   100.0%

```


 Last Updated on 18/09/2024 18:50:48 UTC
<!--END_SECTION:waka-->
