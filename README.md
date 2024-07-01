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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C096%20hrs%209%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               8 hrs 1 min         ███████████████████░░░░░░   76.34% 
HTML                     1 hr                ██░░░░░░░░░░░░░░░░░░░░░░░   9.58% 
Markdown                 54 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.58% 
CSS                      26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.27% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.54%

🔥 Editors: 
VS Code                  10 hrs 30 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           10 hrs 30 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    10 hrs 30 mins      █████████████████████████   100.0%

```


 Last Updated on 01/07/2024 18:44:03 UTC
<!--END_SECTION:waka-->
