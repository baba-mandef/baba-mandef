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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C835%20hrs%2042%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Image (svg)              6 hrs 55 mins       ████████████████░░░░░░░░░   65.92% 
Other                    1 hr 44 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.58% 
Python                   53 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.45% 
HTML                     40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.4% 
TOML                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.4%

🔥 Editors: 
Figma                    6 hrs 55 mins       ████████████████░░░░░░░░░   65.92% 
VS Code                  1 hr 52 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.79% 
Terminal                 1 hr 41 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.06% 
GIMP                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23%

💻 Operating System: 
Mac                      10 hrs 29 mins      █████████████████████████   100.0%

```


 Last Updated on 10/09/2025 18:44:58 UTC
<!--END_SECTION:waka-->
