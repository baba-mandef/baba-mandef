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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C972%20hrs%2048%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 3 mins        ███████████░░░░░░░░░░░░░░   44.71% 
PHP                      1 hr 6 mins         ██████░░░░░░░░░░░░░░░░░░░   23.97% 
Python                   28 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.49% 
Markdown                 24 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.97% 
Image (svg)              19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.05%

🔥 Editors: 
VS Code                  2 hrs 20 mins       ████████████░░░░░░░░░░░░░   51.05% 
Terminal                 1 hr 55 mins        ██████████░░░░░░░░░░░░░░░   41.89% 
Figma                    19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.05%

💻 Operating System: 
Mac                      2 hrs 51 mins       ███████████████░░░░░░░░░░   62.19% 
Linux                    1 hr 44 mins        █████████░░░░░░░░░░░░░░░░   37.81%

```


 Last Updated on 21/01/2026 19:03:51 UTC
<!--END_SECTION:waka-->
