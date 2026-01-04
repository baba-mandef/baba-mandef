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
Python                   8 hrs 28 mins       ██████████░░░░░░░░░░░░░░░   41.61% 
JavaScript               5 hrs 33 mins       ██████░░░░░░░░░░░░░░░░░░░   27.26% 
HTML                     5 hrs 12 mins       ██████░░░░░░░░░░░░░░░░░░░   25.59% 
Other                    1 hr 6 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.43% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

🔥 Editors: 
VS Code                  19 hrs 16 mins      ███████████████████████░░   94.56% 
GIMP                     42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.45% 
Terminal                 13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12% 
Notion                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.86%

💻 Operating System: 
Mac                      20 hrs 22 mins      █████████████████████████   100.0%

```


 Last Updated on 04/01/2026 18:49:11 UTC
<!--END_SECTION:waka-->
