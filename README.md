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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C899%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 31 mins       ██████████████░░░░░░░░░░░   58.67% 
Other                    1 hr 30 mins        ████████░░░░░░░░░░░░░░░░░   35.03% 
Image (svg)              13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.04% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.93% 
Markdown                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

🔥 Editors: 
VS Code                  2 hrs 34 mins       ███████████████░░░░░░░░░░   59.93% 
Terminal                 1 hr 30 mins        ████████░░░░░░░░░░░░░░░░░   35.03% 
Figma                    13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.04%

💻 Operating System: 
Mac                      4 hrs 18 mins       █████████████████████████   100.0%

```


 Last Updated on 24/11/2025 18:50:24 UTC
<!--END_SECTION:waka-->
