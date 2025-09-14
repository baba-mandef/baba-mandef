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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C845%20hrs%208%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 27 mins       ██████████████░░░░░░░░░░░   56.19% 
Image (svg)              3 hrs 5 mins        ████████░░░░░░░░░░░░░░░░░   31.81% 
Other                    30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.22% 
TOML                     24 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.19% 
HTML                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.36%

🔥 Editors: 
VS Code                  6 hrs 7 mins        ███████████████░░░░░░░░░░   63.05% 
Figma                    3 hrs 5 mins        ████████░░░░░░░░░░░░░░░░░   31.81% 
Terminal                 28 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.94% 
GIMP                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

💻 Operating System: 
Mac                      9 hrs 42 mins       █████████████████████████   100.0%

```


 Last Updated on 14/09/2025 18:40:24 UTC
<!--END_SECTION:waka-->
