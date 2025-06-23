###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'name': 'Abiodoun PARAISO',
            'stack': {
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'askme': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'contact': {
                           'Telegram': 'baba_mandef',
                           'Youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C691%20hrs%2016%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 24 mins       ████████████░░░░░░░░░░░░░   51.32% 
HTML                     3 hrs 24 mins       ██████████░░░░░░░░░░░░░░░   39.69% 
Other                    16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23% 
Text                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.18% 
Nginx                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.43%

🔥 Editors: 
VS Code                  8 hrs 34 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    8 hrs 34 mins       █████████████████████████   100.0%

```


 Last Updated on 23/06/2025 18:49:11 UTC
<!--END_SECTION:waka-->
