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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C839%20hrs%2015%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Image (svg)              7 hrs 6 mins        ██████████████░░░░░░░░░░░   59.16% 
Python                   2 hrs 5 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.41% 
Other                    1 hr 42 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.23% 
HTML                     40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.59% 
TOML                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.39%

🔥 Editors: 
Figma                    7 hrs 6 mins        ██████████████░░░░░░░░░░░   59.16% 
VS Code                  3 hrs 14 mins       ██████░░░░░░░░░░░░░░░░░░░   26.93% 
Terminal                 1 hr 38 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.71% 
GIMP                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

💻 Operating System: 
Mac                      12 hrs              █████████████████████████   100.0%

```


 Last Updated on 11/09/2025 18:42:20 UTC
<!--END_SECTION:waka-->
