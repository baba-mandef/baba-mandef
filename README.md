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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C164%20hrs%2059%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   9 hrs 54 mins       ███████████████░░░░░░░░░░   61.21% 
HTML                     5 hrs 10 mins       ████████░░░░░░░░░░░░░░░░░   31.91% 
CSS                      21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22% 
Text                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.09% 
Bash                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55%

🔥 Editors: 
VS Code                  16 hrs 12 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 16 hrs 12 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    16 hrs 12 mins      █████████████████████████   100.0%

```


 Last Updated on 18/10/2024 18:48:21 UTC
<!--END_SECTION:waka-->
