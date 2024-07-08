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
JavaScript               4 hrs 18 mins       ███████████████████████░░   95.03% 
HTML                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.93% 
CSS                      4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.83% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  4 hrs 31 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           4 hrs 28 mins       ████████████████████████░   98.91% 
omural                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.09%

💻 Operating System: 
Linux                    4 hrs 31 mins       █████████████████████████   100.0%

```


 Last Updated on 08/07/2024 18:43:36 UTC
<!--END_SECTION:waka-->
