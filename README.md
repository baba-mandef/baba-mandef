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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C108%20hrs%2032%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     3 hrs 27 mins       ████████████░░░░░░░░░░░░░   50.55% 
Python                   2 hrs 7 mins        ███████░░░░░░░░░░░░░░░░░░   31.15% 
JavaScript               1 hr 4 mins         ████░░░░░░░░░░░░░░░░░░░░░   15.7% 
Markdown                 7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.72% 
Other                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.55%

🔥 Editors: 
VS Code                  6 hrs 50 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           6 hrs 4 mins        ██████████████████████░░░   88.94% 
rezolusoft.com.old       30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.44% 
Unknown Project          14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.62%

💻 Operating System: 
Linux                    6 hrs 50 mins       █████████████████████████   100.0%

```


 Last Updated on 05/08/2024 18:45:15 UTC
<!--END_SECTION:waka-->
