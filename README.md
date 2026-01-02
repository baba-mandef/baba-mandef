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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C952%20hrs%2013%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 40 mins       ██████████░░░░░░░░░░░░░░░   39.61% 
HTML                     5 hrs               ████████░░░░░░░░░░░░░░░░░   34.97% 
JavaScript               2 hrs 34 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.92% 
Other                    1 hr 3 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   7.36% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12%

🔥 Editors: 
VS Code                  13 hrs 17 mins      ███████████████████████░░   92.62% 
GIMP                     42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.91% 
Terminal                 13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55% 
Notion                   7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.92%

💻 Operating System: 
Mac                      14 hrs 20 mins      █████████████████████████   100.0%

```


 Last Updated on 02/01/2026 18:50:08 UTC
<!--END_SECTION:waka-->
