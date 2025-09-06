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
                       'languages': ['Python', 'JS', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'English', 'French'],
                       'tools': ['Django', 'React', 'Flet', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C832%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 40 mins       █████████░░░░░░░░░░░░░░░░   39.16% 
Image (svg)              2 hrs 52 mins       ███████░░░░░░░░░░░░░░░░░░   30.57% 
Other                    2 hrs 16 mins       ██████░░░░░░░░░░░░░░░░░░░   24.13% 
Text                     21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.75% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.2%

🔥 Editors: 
VS Code                  4 hrs 20 mins       ███████████░░░░░░░░░░░░░░   46.24% 
Figma                    2 hrs 52 mins       ███████░░░░░░░░░░░░░░░░░░   30.57% 
Terminal                 1 hr 38 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.4% 
Notion                   20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.55% 
GIMP                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.24%

💻 Operating System: 
Mac                      9 hrs 23 mins       █████████████████████████   100.0%

```


 Last Updated on 06/09/2025 18:40:53 UTC
<!--END_SECTION:waka-->
