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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C169%20hrs%2030%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   10 hrs 52 mins      ████████████░░░░░░░░░░░░░   50.91% 
HTML                     8 hrs 48 mins       ██████████░░░░░░░░░░░░░░░   41.26% 
CSS                      28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.2% 
Text                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.94% 
JavaScript               22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.73%

🔥 Editors: 
VS Code                  21 hrs 21 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 21 hrs 18 mins      █████████████████████████   99.78% 
back-end                 2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.22%

💻 Operating System: 
Linux                    21 hrs 21 mins      █████████████████████████   100.0%

```


 Last Updated on 20/10/2024 18:47:57 UTC
<!--END_SECTION:waka-->
