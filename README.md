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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C167%20hrs%2011%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   9 hrs 10 mins       █████████████░░░░░░░░░░░░   54.04% 
HTML                     6 hrs 33 mins       █████████░░░░░░░░░░░░░░░░   38.63% 
CSS                      28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.76% 
Text                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95% 
Bash                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.48%

🔥 Editors: 
VS Code                  16 hrs 59 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 16 hrs 59 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    16 hrs 59 mins      █████████████████████████   100.0%

```


 Last Updated on 19/10/2024 18:46:04 UTC
<!--END_SECTION:waka-->
