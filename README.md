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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C208%20hrs%2018%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     3 hrs 47 mins       ████████████░░░░░░░░░░░░░   51.47% 
Python                   3 hrs 1 min         ██████████░░░░░░░░░░░░░░░   41.16% 
Text                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23% 
JavaScript               12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.86% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.39%

🔥 Editors: 
VS Code                  7 hrs 21 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    6 hrs 22 mins       █████████████████████░░░░   86.6% 
rezolusoft.com           33 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.51% 
ekilibre                 13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.11% 
api.abiodoun.dev         12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.78%

💻 Operating System: 
Linux                    7 hrs 21 mins       █████████████████████████   100.0%

```


 Last Updated on 12/11/2024 18:49:39 UTC
<!--END_SECTION:waka-->
