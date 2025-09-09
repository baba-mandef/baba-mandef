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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C835%20hrs%2042%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Image (svg)              7 hrs 10 mins       █████████████░░░░░░░░░░░░   53.49% 
Python                   2 hrs 52 mins       █████░░░░░░░░░░░░░░░░░░░░   21.45% 
Other                    2 hrs 7 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.83% 
HTML                     40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.0% 
Text                     21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.62%

🔥 Editors: 
Figma                    7 hrs 10 mins       █████████████░░░░░░░░░░░░   53.49% 
VS Code                  4 hrs 9 mins        ███████░░░░░░░░░░░░░░░░░░   30.91% 
Terminal                 1 hr 51 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.89% 
GIMP                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.72%

💻 Operating System: 
Mac                      13 hrs 25 mins      █████████████████████████   100.0%

```


 Last Updated on 09/09/2025 18:42:47 UTC
<!--END_SECTION:waka-->
