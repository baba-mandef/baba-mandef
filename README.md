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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C089%20hrs%2038%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               5 hrs 28 mins       ███████████████████░░░░░░   76.79% 
HTML                     45 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.74% 
CSS                      23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.51% 
Markdown                 22 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.27% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.88%

🔥 Editors: 
VS Code                  7 hrs 7 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           5 hrs 36 mins       ███████████████████░░░░░░   78.71% 
Ustaarabu.org            1 hr 29 mins        █████░░░░░░░░░░░░░░░░░░░░   20.99% 
kreativ.inc              1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3%

💻 Operating System: 
Linux                    7 hrs 7 mins        █████████████████████████   100.0%

```


 Last Updated on 28/06/2024 18:43:24 UTC
<!--END_SECTION:waka-->
