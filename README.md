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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C097%20hrs%2036%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               11 hrs 1 min        ████████████████████░░░░░   83.36% 
Markdown                 54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.82% 
HTML                     39 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.03% 
CSS                      29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.75% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44%

🔥 Editors: 
VS Code                  13 hrs 13 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           13 hrs 10 mins      █████████████████████████   99.63% 
omural                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.37%

💻 Operating System: 
Linux                    13 hrs 13 mins      █████████████████████████   100.0%

```


 Last Updated on 03/07/2024 18:41:44 UTC
<!--END_SECTION:waka-->
