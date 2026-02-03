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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C982%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 4 mins        ███████████████░░░░░░░░░░   62.93% 
Other                    1 hr 58 mins        ██████░░░░░░░░░░░░░░░░░░░   24.43% 
HTML                     26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.47% 
Image (svg)              23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.87% 
Bash                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.45%

🔥 Editors: 
VS Code                  5 hrs 41 mins       █████████████████░░░░░░░░   70.7% 
Terminal                 1 hr 18 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.32% 
GIMP                     28 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.94% 
Figma                    23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.87% 
FileZilla                10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.13%

💻 Operating System: 
Mac                      8 hrs 3 mins        █████████████████████████   100.0%

```


 Last Updated on 03/02/2026 19:24:26 UTC
<!--END_SECTION:waka-->
