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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C826%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 55 mins       ███████████████░░░░░░░░░░   60.02% 
Other                    1 hr 20 mins        █████░░░░░░░░░░░░░░░░░░░░   20.61% 
Image (svg)              41 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.63% 
Text                     21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.38% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15%

🔥 Editors: 
VS Code                  4 hrs 33 mins       █████████████████░░░░░░░░   69.64% 
Notion                   43 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.13% 
Figma                    41 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.63% 
Terminal                 21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.46% 
GIMP                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15%

💻 Operating System: 
Mac                      6 hrs 32 mins       █████████████████████████   100.0%

```


 Last Updated on 03/09/2025 18:42:36 UTC
<!--END_SECTION:waka-->
