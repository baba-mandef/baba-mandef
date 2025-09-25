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
Other                    1 hr 25 mins        ██████████████████░░░░░░░   74.06% 
Python                   24 mins             █████░░░░░░░░░░░░░░░░░░░░   21.02% 
HTML                     5 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.53% 
Image (svg)              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
Notes                    38 mins             ████████░░░░░░░░░░░░░░░░░   33.02% 
VS Code                  29 mins             ██████░░░░░░░░░░░░░░░░░░░   25.55% 
GIMP                     27 mins             ██████░░░░░░░░░░░░░░░░░░░   23.81% 
Terminal                 19 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.26% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36%

💻 Operating System: 
Mac                      1 hr 55 mins        █████████████████████████   100.0%

```


 Last Updated on 25/09/2025 18:46:16 UTC
<!--END_SECTION:waka-->
