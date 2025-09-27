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
Other                    1 hr 12 mins        ██████████████████░░░░░░░   74.5% 
Python                   24 mins             ██████░░░░░░░░░░░░░░░░░░░   25.04% 
Image (svg)              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
Notes                    40 mins             ██████████░░░░░░░░░░░░░░░   41.28% 
VS Code                  24 mins             ██████░░░░░░░░░░░░░░░░░░░   25.04% 
Terminal                 21 mins             █████░░░░░░░░░░░░░░░░░░░░   21.79% 
GIMP                     11 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.46% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

💻 Operating System: 
Mac                      1 hr 37 mins        █████████████████████████   100.0%

```


 Last Updated on 27/09/2025 18:41:39 UTC
<!--END_SECTION:waka-->
