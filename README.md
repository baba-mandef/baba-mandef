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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C895%20hrs%2042%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 3 mins        ██████████████████░░░░░░░   72.14% 
Other                    1 hr 13 mins        █████░░░░░░░░░░░░░░░░░░░░   21.71% 
Image (svg)              19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.69% 
SQL                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28% 
TOML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

🔥 Editors: 
VS Code                  4 hrs 5 mins        ██████████████████░░░░░░░   72.61% 
Terminal                 1 hr 13 mins        █████░░░░░░░░░░░░░░░░░░░░   21.71% 
Figma                    19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.69%

💻 Operating System: 
Mac                      5 hrs 37 mins       █████████████████████████   100.0%

```


 Last Updated on 22/11/2025 18:44:51 UTC
<!--END_SECTION:waka-->
