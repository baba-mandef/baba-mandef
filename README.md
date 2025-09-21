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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C854%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 19 mins       █████████████████░░░░░░░░   71.42% 
Other                    2 hrs 26 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.65% 
HTML                     36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.7% 
Image (svg)              30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.86% 
TOML                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.22%

🔥 Editors: 
VS Code                  10 hrs 7 mins       ███████████████████░░░░░░   77.49% 
GIMP                     1 hr 25 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.92% 
Terminal                 1 hr                ██░░░░░░░░░░░░░░░░░░░░░░░   7.73% 
Figma                    30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.86%

💻 Operating System: 
Mac                      13 hrs 3 mins       █████████████████████████   100.0%

```


 Last Updated on 21/09/2025 18:42:38 UTC
<!--END_SECTION:waka-->
