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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C105%20hrs%2017%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               2 hrs 1 min         █████████████████░░░░░░░░   69.11% 
HTML                     51 mins             ███████░░░░░░░░░░░░░░░░░░   29.67% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.62% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.58% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
VS Code                  2 hrs 55 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           1 hr 51 mins        ████████████████░░░░░░░░░   63.63% 
omural                   36 mins             █████░░░░░░░░░░░░░░░░░░░░   20.82% 
omural2                  27 mins             ████░░░░░░░░░░░░░░░░░░░░░   15.55%

💻 Operating System: 
Linux                    2 hrs 55 mins       █████████████████████████   100.0%

```


 Last Updated on 20/07/2024 18:46:18 UTC
<!--END_SECTION:waka-->
