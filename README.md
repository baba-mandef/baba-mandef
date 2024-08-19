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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C128%20hrs%2042%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   7 hrs 39 mins       ████████████░░░░░░░░░░░░░   48.63% 
HTML                     6 hrs 50 mins       ██████████░░░░░░░░░░░░░░░   43.45% 
CSS                      23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.45% 
Text                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.19% 
Git Config               13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.4%

🔥 Editors: 
VS Code                  15 hrs 45 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           15 hrs 45 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    15 hrs 45 mins      █████████████████████████   100.0%

```


 Last Updated on 19/08/2024 18:46:00 UTC
<!--END_SECTION:waka-->
