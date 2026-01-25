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
Other                    1 hr 25 mins        ████████░░░░░░░░░░░░░░░░░   33.58% 
PHP                      1 hr 6 mins         ██████░░░░░░░░░░░░░░░░░░░   25.79% 
Python                   45 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.88% 
Markdown                 24 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.65% 
Image (svg)              20 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.93%

🔥 Editors: 
VS Code                  2 hrs 36 mins       ███████████████░░░░░░░░░░   61.33% 
Terminal                 1 hr 18 mins        ███████░░░░░░░░░░░░░░░░░░   30.75% 
Figma                    20 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.93%

💻 Operating System: 
Mac                      2 hrs 31 mins       ██████████████░░░░░░░░░░░   59.32% 
Linux                    1 hr 44 mins        ██████████░░░░░░░░░░░░░░░   40.68%

```


 Last Updated on 25/01/2026 18:51:15 UTC
<!--END_SECTION:waka-->
