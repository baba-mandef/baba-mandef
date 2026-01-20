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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C970%20hrs%2027%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 25 mins        ██████████░░░░░░░░░░░░░░░   42.1% 
PHP                      1 hr 5 mins         ████████░░░░░░░░░░░░░░░░░   32.26% 
Markdown                 24 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.15% 
Python                   14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.98% 
CSS                      13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.51%

🔥 Editors: 
VS Code                  1 hr 58 mins        ██████████████░░░░░░░░░░░   58.45% 
Terminal                 1 hr 24 mins        ██████████░░░░░░░░░░░░░░░   41.55%

💻 Operating System: 
Linux                    1 hr 44 mins        ████████████░░░░░░░░░░░░░   51.24% 
Mac                      1 hr 39 mins        ████████████░░░░░░░░░░░░░   48.76%

```


 Last Updated on 20/01/2026 19:38:06 UTC
<!--END_SECTION:waka-->
