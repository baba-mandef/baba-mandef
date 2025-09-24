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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C856%20hrs%2030%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 38 mins       ███████████░░░░░░░░░░░░░░   47.15% 
Python                   2 hrs 13 mins       ██████████░░░░░░░░░░░░░░░   39.84% 
HTML                     36 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.96% 
Image (svg)              6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.87% 
TOML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

🔥 Editors: 
VS Code                  2 hrs 51 mins       ████████████░░░░░░░░░░░░░   50.98% 
Terminal                 1 hr 5 mins         ████░░░░░░░░░░░░░░░░░░░░░   19.47% 
GIMP                     54 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.33% 
Notes                    38 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.36% 
Figma                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.87%

💻 Operating System: 
Mac                      5 hrs 36 mins       █████████████████████████   100.0%

```


 Last Updated on 24/09/2025 18:44:02 UTC
<!--END_SECTION:waka-->
