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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C982%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 1 min         █████████████░░░░░░░░░░░░   52.16% 
Other                    1 hr 53 mins        ████████░░░░░░░░░░░░░░░░░   32.57% 
HTML                     26 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.57% 
Image (svg)              12 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.64% 
Bash                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.96%

🔥 Editors: 
VS Code                  3 hrs 41 mins       ████████████████░░░░░░░░░   63.78% 
Terminal                 1 hr 18 mins        █████░░░░░░░░░░░░░░░░░░░░   22.69% 
GIMP                     28 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.26% 
Figma                    12 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.64% 
FileZilla                5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.63%

💻 Operating System: 
Mac                      5 hrs 47 mins       █████████████████████████   100.0%

```


 Last Updated on 04/02/2026 19:12:34 UTC
<!--END_SECTION:waka-->
