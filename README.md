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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C974%20hrs%2012%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 6 mins        ██████████░░░░░░░░░░░░░░░   43.28% 
PHP                      1 hr 6 mins         █████░░░░░░░░░░░░░░░░░░░░   22.59% 
Python                   41 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.22% 
Markdown                 24 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.45% 
Image (svg)              20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.94%

🔥 Editors: 
VS Code                  2 hrs 33 mins       █████████████░░░░░░░░░░░░   52.43% 
Terminal                 1 hr 58 mins        ██████████░░░░░░░░░░░░░░░   40.62% 
Figma                    20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.94%

💻 Operating System: 
Mac                      3 hrs 8 mins        ████████████████░░░░░░░░░   64.37% 
Linux                    1 hr 44 mins        █████████░░░░░░░░░░░░░░░░   35.63%

```


 Last Updated on 22/01/2026 18:57:35 UTC
<!--END_SECTION:waka-->
