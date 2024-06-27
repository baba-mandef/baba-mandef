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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C088%20hrs%2036%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               3 hrs 1 min         ███████████████████░░░░░░   77.74% 
HTML                     39 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.02% 
CSS                      8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.49% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.6% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

🔥 Editors: 
VS Code                  3 hrs 54 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           2 hrs 23 mins       ███████████████░░░░░░░░░░   61.15% 
Ustaarabu.org            1 hr 29 mins        █████████░░░░░░░░░░░░░░░░   38.3% 
kreativ.inc              1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.55%

💻 Operating System: 
Linux                    3 hrs 54 mins       █████████████████████████   100.0%

```


 Last Updated on 27/06/2024 18:41:52 UTC
<!--END_SECTION:waka-->
