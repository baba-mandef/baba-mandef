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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C130%20hrs%2016%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     5 hrs 26 mins       ███████████░░░░░░░░░░░░░░   46.81% 
Python                   4 hrs 58 mins       ██████████░░░░░░░░░░░░░░░   42.76% 
Text                     25 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.6% 
CSS                      22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.18% 
Git Config               13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.9%

🔥 Editors: 
VS Code                  11 hrs 38 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           11 hrs 38 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    11 hrs 38 mins      █████████████████████████   100.0%

```


 Last Updated on 22/08/2024 18:47:26 UTC
<!--END_SECTION:waka-->
