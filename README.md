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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C974%20hrs%2050%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 44 mins       ██████████████████████░░░   88.34% 
Image (svg)              11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.28% 
Other                    9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.13% 
TOML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19% 
HTML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

🔥 Editors: 
VS Code                  2 hrs 45 mins       ██████████████████████░░░   88.59% 
Figma                    11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.28% 
Terminal                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.53% 
FileZilla                4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.47% 
Notion                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

💻 Operating System: 
Mac                      3 hrs 6 mins        █████████████████████████   100.0%

```


 Last Updated on 28/01/2026 18:59:03 UTC
<!--END_SECTION:waka-->
