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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C086%20hrs%2047%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               1 hr 37 mins        █████████████████░░░░░░░░   67.71% 
HTML                     34 mins             ██████░░░░░░░░░░░░░░░░░░░   24.07% 
CSS                      7 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.37% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.61% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21%

🔥 Editors: 
VS Code                  2 hrs 24 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
Ustaarabu.org            1 hr 29 mins        ███████████████░░░░░░░░░░   62.25% 
rezolusoft.com           53 mins             █████████░░░░░░░░░░░░░░░░   36.85% 
kreativ.inc              1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.9%

💻 Operating System: 
Linux                    2 hrs 24 mins       █████████████████████████   100.0%

```


 Last Updated on 25/06/2024 18:45:04 UTC
<!--END_SECTION:waka-->
