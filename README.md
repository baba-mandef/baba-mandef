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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C974%20hrs%2050%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 27 mins        ████████░░░░░░░░░░░░░░░░░   32.11% 
PHP                      1 hr 6 mins         ██████░░░░░░░░░░░░░░░░░░░   24.34% 
Python                   59 mins             █████░░░░░░░░░░░░░░░░░░░░   22.1% 
Markdown                 24 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.11% 
Image (svg)              20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.48%

🔥 Editors: 
VS Code                  2 hrs 51 mins       ███████████████░░░░░░░░░░   63.27% 
Terminal                 1 hr 19 mins        ███████░░░░░░░░░░░░░░░░░░   29.25% 
Figma                    20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.48%

💻 Operating System: 
Mac                      2 hrs 47 mins       ███████████████░░░░░░░░░░   61.62% 
Linux                    1 hr 44 mins        █████████░░░░░░░░░░░░░░░░   38.38%

```


 Last Updated on 24/01/2026 18:50:44 UTC
<!--END_SECTION:waka-->
