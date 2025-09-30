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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C856%20hrs%2050%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 24 mins        █████████████████████░░░░   86.36% 
Python                   12 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.18% 
Image (svg)              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
Notes                    57 mins             ██████████████░░░░░░░░░░░   58.41% 
Terminal                 16 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.64% 
VS Code                  12 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.18% 
GIMP                     11 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.35% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

💻 Operating System: 
Mac                      1 hr 37 mins        █████████████████████████   100.0%

```


 Last Updated on 30/09/2025 18:44:44 UTC
<!--END_SECTION:waka-->
