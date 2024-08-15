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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C116%20hrs%2028%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   4 hrs 17 mins       █████████████████░░░░░░░░   69.79% 
HTML                     1 hr 36 mins        ██████░░░░░░░░░░░░░░░░░░░   26.3% 
Markdown                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.72% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.03% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89%

🔥 Editors: 
VS Code                  6 hrs 8 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           6 hrs 8 mins        █████████████████████████   100.0%

💻 Operating System: 
Linux                    6 hrs 8 mins        █████████████████████████   100.0%

```


 Last Updated on 15/08/2024 18:45:54 UTC
<!--END_SECTION:waka-->
