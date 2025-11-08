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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C875%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 6 mins        ███████████░░░░░░░░░░░░░░   47.32% 
HTML                     1 hr 59 mins        ███████████░░░░░░░░░░░░░░   44.9% 
Python                   14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.59% 
Image (svg)              5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.88% 
Markdown                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

🔥 Editors: 
VS Code                  2 hrs 15 mins       ████████████░░░░░░░░░░░░░   50.71% 
Notion                   1 hr 20 mins        ███████░░░░░░░░░░░░░░░░░░   30.18% 
Terminal                 24 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.04% 
GIMP                     21 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.94% 
Figma                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.88%

💻 Operating System: 
Mac                      4 hrs 27 mins       █████████████████████████   100.0%

```


 Last Updated on 08/11/2025 18:44:09 UTC
<!--END_SECTION:waka-->
