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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C965%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   7 hrs 4 mins        ██████████░░░░░░░░░░░░░░░   40.12% 
JavaScript               4 hrs 43 mins       ██████░░░░░░░░░░░░░░░░░░░   26.73% 
HTML                     4 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   25.05% 
Other                    1 hr 24 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.98% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

🔥 Editors: 
VS Code                  16 hrs 14 mins      ███████████████████████░░   92.02% 
GIMP                     42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.99% 
Notion                   23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26% 
Terminal                 18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.73%

💻 Operating System: 
Mac                      17 hrs 38 mins      █████████████████████████   100.0%

```


 Last Updated on 06/01/2026 18:52:04 UTC
<!--END_SECTION:waka-->
