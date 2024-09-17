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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C144%20hrs%2029%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     12 hrs 4 mins       ██████████████████░░░░░░░   74.48% 
Python                   2 hrs 55 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.03% 
CSS                      46 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.77% 
Text                     17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.77% 
Markdown                 5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.54%

🔥 Editors: 
VS Code                  16 hrs 12 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    16 hrs 7 mins       █████████████████████████   99.52% 
omural                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.48%

💻 Operating System: 
Linux                    16 hrs 12 mins      █████████████████████████   100.0%

```


 Last Updated on 17/09/2024 18:50:44 UTC
<!--END_SECTION:waka-->
