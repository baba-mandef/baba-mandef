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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C183%20hrs%204%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     4 hrs 33 mins       ████████████░░░░░░░░░░░░░   51.47% 
Python                   3 hrs 50 mins       ██████████░░░░░░░░░░░░░░░   43.42% 
Text                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.25% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.34% 
JavaScript               5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.0%

🔥 Editors: 
VS Code                  8 hrs 50 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 7 hrs 37 mins       █████████████████████░░░░   86.18% 
omural                   37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.0% 
hudim                    29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.58% 
back-end                 3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.65% 
api.abiodoun.dev         3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.58%

💻 Operating System: 
Linux                    8 hrs 50 mins       █████████████████████████   100.0%

```


 Last Updated on 27/10/2024 18:48:17 UTC
<!--END_SECTION:waka-->
