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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C829%20hrs%2042%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 55 mins       ██████████████░░░░░░░░░░░   57.67% 
Other                    1 hr 27 mins        █████░░░░░░░░░░░░░░░░░░░░   21.45% 
Image (svg)              50 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.47% 
Text                     21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.17% 
JSON                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.03%

🔥 Editors: 
VS Code                  4 hrs 33 mins       ████████████████░░░░░░░░░   66.92% 
Figma                    50 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.47% 
Notion                   43 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.7% 
Terminal                 28 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.88% 
GIMP                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.02%

💻 Operating System: 
Mac                      6 hrs 48 mins       █████████████████████████   100.0%

```


 Last Updated on 05/09/2025 18:43:47 UTC
<!--END_SECTION:waka-->
