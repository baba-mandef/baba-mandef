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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C838%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Image (svg)              7 hrs 8 mins        █████████████░░░░░░░░░░░░   55.42% 
Python                   2 hrs 55 mins       █████░░░░░░░░░░░░░░░░░░░░   22.75% 
Other                    1 hr 42 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.25% 
HTML                     40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.21% 
TOML                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.16%

🔥 Editors: 
Figma                    7 hrs 8 mins        █████████████░░░░░░░░░░░░   55.42% 
VS Code                  4 hrs 4 mins        ████████░░░░░░░░░░░░░░░░░   31.62% 
Terminal                 1 hr 38 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.77% 
GIMP                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

💻 Operating System: 
Mac                      12 hrs 53 mins      █████████████████████████   100.0%

```


 Last Updated on 12/09/2025 18:41:31 UTC
<!--END_SECTION:waka-->
