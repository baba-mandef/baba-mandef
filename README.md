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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C097%20hrs%2017%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               7 hrs 19 mins       ███████████████████░░░░░░   77.49% 
Markdown                 54 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.53% 
HTML                     37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.67% 
CSS                      27 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.92% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.62%

🔥 Editors: 
VS Code                  9 hrs 27 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           9 hrs 24 mins       ████████████████████████░   99.48% 
omural                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52%

💻 Operating System: 
Linux                    9 hrs 27 mins       █████████████████████████   100.0%

```


 Last Updated on 02/07/2024 18:42:46 UTC
<!--END_SECTION:waka-->
