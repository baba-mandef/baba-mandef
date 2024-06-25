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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C085%20hrs%2015%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               1 hr 2 mins         █████████████████░░░░░░░░   68.07% 
HTML                     19 mins             █████░░░░░░░░░░░░░░░░░░░░   20.72% 
CSS                      6 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.76% 
JSON                     3 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.07% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32%

🔥 Editors: 
VS Code                  1 hr 32 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
Ustaarabu.org            1 hr 29 mins        ████████████████████████░   97.25% 
kreativ.inc              1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.41% 
rezolusoft.com           1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.35%

💻 Operating System: 
Linux                    1 hr 32 mins        █████████████████████████   100.0%

```


 Last Updated on 24/06/2024 18:44:00 UTC
<!--END_SECTION:waka-->
