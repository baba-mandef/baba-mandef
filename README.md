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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C965%20hrs%2026%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 28 mins       ██████████░░░░░░░░░░░░░░░   42.04% 
JavaScript               5 hrs 33 mins       ███████░░░░░░░░░░░░░░░░░░   27.55% 
HTML                     4 hrs 42 mins       █████░░░░░░░░░░░░░░░░░░░░   23.33% 
Other                    1 hr 24 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.98% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

🔥 Editors: 
VS Code                  18 hrs 45 mins      ███████████████████████░░   93.02% 
GIMP                     42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.49% 
Notion                   23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.98% 
Terminal                 18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.52%

💻 Operating System: 
Mac                      20 hrs 10 mins      █████████████████████████   100.0%

```


 Last Updated on 05/01/2026 18:54:01 UTC
<!--END_SECTION:waka-->
