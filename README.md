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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C150%20hrs%2017%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     12 hrs 25 mins      ███████████████████░░░░░░   78.83% 
Python                   2 hrs 19 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.76% 
CSS                      56 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.93% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.4% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  15 hrs 45 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    15 hrs 40 mins      █████████████████████████   99.5% 
omural                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5%

💻 Operating System: 
Linux                    15 hrs 45 mins      █████████████████████████   100.0%

```


 Last Updated on 19/09/2024 18:47:14 UTC
<!--END_SECTION:waka-->
