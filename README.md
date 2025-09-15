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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C848%20hrs%2013%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 11 mins       ███████████████████░░░░░░   76.94% 
Image (svg)              1 hr 33 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.59% 
TOML                     24 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.82% 
Other                    14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.29% 
HTML                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.15%

🔥 Editors: 
VS Code                  8 hrs 51 mins       ████████████████████░░░░░   83.19% 
Figma                    1 hr 33 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.59% 
Terminal                 13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.03% 
GIMP                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

💻 Operating System: 
Mac                      10 hrs 39 mins      █████████████████████████   100.0%

```


 Last Updated on 15/09/2025 18:45:23 UTC
<!--END_SECTION:waka-->
