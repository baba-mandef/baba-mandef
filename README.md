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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C835%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Image (svg)              5 hrs 30 mins       ████████████░░░░░░░░░░░░░   48.81% 
Python                   2 hrs 50 mins       ██████░░░░░░░░░░░░░░░░░░░   25.17% 
Other                    1 hr 55 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.1% 
HTML                     26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.92% 
Text                     21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.12%

🔥 Editors: 
Figma                    5 hrs 30 mins       ████████████░░░░░░░░░░░░░   48.81% 
VS Code                  3 hrs 56 mins       ████████░░░░░░░░░░░░░░░░░   34.87% 
Terminal                 1 hr 37 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.46% 
GIMP                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.86%

💻 Operating System: 
Mac                      11 hrs 17 mins      █████████████████████████   100.0%

```


 Last Updated on 07/09/2025 18:41:13 UTC
<!--END_SECTION:waka-->
