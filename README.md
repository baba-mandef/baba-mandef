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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C890%20hrs%2051%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   11 hrs 18 mins      ███████████████████░░░░░░   77.14% 
Other                    1 hr 39 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   11.29% 
Image (svg)              30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.5% 
JavaScript               29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.38% 
JSON                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.28%

🔥 Editors: 
VS Code                  12 hrs 29 mins      █████████████████████░░░░   85.18% 
Terminal                 1 hr 8 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   7.76% 
Figma                    30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.5% 
GIMP                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.8% 
Notion                   6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.73%

💻 Operating System: 
Mac                      14 hrs 39 mins      █████████████████████████   100.0%

```


 Last Updated on 13/11/2025 18:48:14 UTC
<!--END_SECTION:waka-->
