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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C854%20hrs%2057%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 28 mins       █████████████████░░░░░░░░   69.38% 
Other                    2 hrs 27 mins       █████░░░░░░░░░░░░░░░░░░░░   20.11% 
HTML                     36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.03% 
Image (svg)              29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.02% 
TOML                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.31%

🔥 Editors: 
VS Code                  9 hrs 15 mins       ███████████████████░░░░░░   75.87% 
GIMP                     1 hr 25 mins        ███░░░░░░░░░░░░░░░░░░░░░░   11.68% 
Terminal                 1 hr 1 min          ██░░░░░░░░░░░░░░░░░░░░░░░   8.42% 
Figma                    29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.02%

💻 Operating System: 
Mac                      12 hrs 12 mins      █████████████████████████   100.0%

```


 Last Updated on 22/09/2025 18:44:35 UTC
<!--END_SECTION:waka-->
