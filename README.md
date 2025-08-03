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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C746%20hrs%2026%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 1 min         ███████████████░░░░░░░░░░   59.72% 
HTML                     1 hr 39 mins        ████████░░░░░░░░░░░░░░░░░   32.81% 
TOML                     13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.52% 
Git Config               8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.71% 
CSS                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

🔥 Editors: 
VS Code                  5 hrs 3 mins        █████████████████████████   100.0%

💻 Operating System: 
Mac                      4 hrs 57 mins       ████████████████████████░   98.04% 
Linux                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.96%

```


 Last Updated on 03/08/2025 18:50:17 UTC
<!--END_SECTION:waka-->
