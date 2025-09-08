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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C833%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Image (svg)              7 hrs 19 mins       █████████████░░░░░░░░░░░░   55.19% 
Python                   2 hrs 50 mins       █████░░░░░░░░░░░░░░░░░░░░   21.37% 
Other                    2 hrs 6 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.86% 
HTML                     26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.34% 
Text                     21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.65%

🔥 Editors: 
Figma                    7 hrs 19 mins       █████████████░░░░░░░░░░░░   55.19% 
VS Code                  3 hrs 52 mins       ███████░░░░░░░░░░░░░░░░░░   29.18% 
Terminal                 1 hr 51 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.04% 
GIMP                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.59%

💻 Operating System: 
Mac                      13 hrs 16 mins      █████████████████████████   100.0%

```


 Last Updated on 08/09/2025 18:45:01 UTC
<!--END_SECTION:waka-->
