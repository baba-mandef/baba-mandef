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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C088%20hrs%208%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               2 hrs 1 min         █████████████████░░░░░░░░   70.84% 
HTML                     38 mins             █████░░░░░░░░░░░░░░░░░░░░   22.26% 
CSS                      7 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.51% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.19% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

🔥 Editors: 
VS Code                  2 hrs 51 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
Ustaarabu.org            1 hr 29 mins        █████████████░░░░░░░░░░░░   52.29% 
rezolusoft.com           1 hr 20 mins        ███████████░░░░░░░░░░░░░░   46.95% 
kreativ.inc              1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.76%

💻 Operating System: 
Linux                    2 hrs 51 mins       █████████████████████████   100.0%

```


 Last Updated on 26/06/2024 18:45:37 UTC
<!--END_SECTION:waka-->
