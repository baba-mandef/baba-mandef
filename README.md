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
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'AskMe': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C196%20hrs%203%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     5 hrs 17 mins       █████████░░░░░░░░░░░░░░░░   35.61% 
Python                   3 hrs 56 mins       ██████░░░░░░░░░░░░░░░░░░░   26.56% 
JavaScript               3 hrs 29 mins       █████░░░░░░░░░░░░░░░░░░░░   23.49% 
JSON                     54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.15% 
Text                     27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.06%

🔥 Editors: 
VS Code                  14 hrs 50 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    7 hrs 1 min         ███████████░░░░░░░░░░░░░░   47.38% 
abiodoun.dev             4 hrs 42 mins       ████████░░░░░░░░░░░░░░░░░   31.77% 
api.abiodoun.dev         2 hrs 10 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.7% 
rezolusoft.com           54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.15%

💻 Operating System: 
Linux                    14 hrs 50 mins      █████████████████████████   100.0%

```


 Last Updated on 04/11/2024 18:48:51 UTC
<!--END_SECTION:waka-->
