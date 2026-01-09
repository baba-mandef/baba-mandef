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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C969%20hrs%2031%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    3 hrs 58 mins       ████████░░░░░░░░░░░░░░░░░   34.92% 
JavaScript               2 hrs 59 mins       ██████░░░░░░░░░░░░░░░░░░░   26.18% 
Python                   2 hrs 47 mins       ██████░░░░░░░░░░░░░░░░░░░   24.54% 
HTML                     1 hr 38 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.36%

🔥 Editors: 
VS Code                  7 hrs 25 mins       ████████████████░░░░░░░░░   65.1% 
GIMP                     3 hrs 2 mins        ██████░░░░░░░░░░░░░░░░░░░   26.62% 
Terminal                 40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.94% 
Notion                   15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.33%

💻 Operating System: 
Mac                      11 hrs 24 mins      █████████████████████████   100.0%

```


 Last Updated on 09/01/2026 18:53:35 UTC
<!--END_SECTION:waka-->
