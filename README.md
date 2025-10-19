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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C864%20hrs%2015%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 12 mins        ███████████████████████░░   93.8% 
Python                   4 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.55% 
XML                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.62% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
Notion                   1 hr                ███████████████████░░░░░░   77.7% 
Terminal                 8 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   10.83% 
VS Code                  4 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.17% 
GIMP                     3 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.03% 
Notes                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26%

💻 Operating System: 
Mac                      1 hr 17 mins        █████████████████████████   100.0%

```


 Last Updated on 19/10/2025 18:42:36 UTC
<!--END_SECTION:waka-->
