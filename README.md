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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C974%20hrs%2031%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs               ██████████░░░░░░░░░░░░░░░   42.07% 
PHP                      1 hr 6 mins         █████░░░░░░░░░░░░░░░░░░░░   23.07% 
Python                   41 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.52% 
Markdown                 24 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.63% 
Image (svg)              20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.09%

🔥 Editors: 
VS Code                  2 hrs 33 mins       █████████████░░░░░░░░░░░░   53.55% 
Terminal                 1 hr 52 mins        █████████░░░░░░░░░░░░░░░░   39.36% 
Figma                    20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.09%

💻 Operating System: 
Mac                      3 hrs 2 mins        ████████████████░░░░░░░░░   63.61% 
Linux                    1 hr 44 mins        █████████░░░░░░░░░░░░░░░░   36.39%

```


 Last Updated on 23/01/2026 18:56:30 UTC
<!--END_SECTION:waka-->
