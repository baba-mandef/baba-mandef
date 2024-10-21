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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C174%20hrs%2043%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   14 hrs 12 mins      ████████████░░░░░░░░░░░░░   49.47% 
HTML                     12 hrs 42 mins      ███████████░░░░░░░░░░░░░░   44.24% 
CSS                      28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.63% 
JavaScript               27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.6% 
Text                     25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.46%

🔥 Editors: 
VS Code                  28 hrs 43 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 28 hrs 34 mins      ████████████████████████░   99.46% 
back-end                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.37% 
api.abiodoun.dev         3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

💻 Operating System: 
Linux                    28 hrs 43 mins      █████████████████████████   100.0%

```


 Last Updated on 21/10/2024 18:48:53 UTC
<!--END_SECTION:waka-->
