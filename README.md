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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C842%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Image (svg)              5 hrs 42 mins       ███████████░░░░░░░░░░░░░░   47.29% 
Python                   4 hrs 45 mins       █████████░░░░░░░░░░░░░░░░   39.4% 
HTML                     40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.56% 
Other                    30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.19% 
TOML                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.37%

🔥 Editors: 
VS Code                  5 hrs 52 mins       ████████████░░░░░░░░░░░░░   48.58% 
Figma                    5 hrs 42 mins       ███████████░░░░░░░░░░░░░░   47.29% 
Terminal                 28 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.97% 
GIMP                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

💻 Operating System: 
Mac                      12 hrs 4 mins       █████████████████████████   100.0%

```


 Last Updated on 13/09/2025 18:40:02 UTC
<!--END_SECTION:waka-->
