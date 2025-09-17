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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C852%20hrs%2043%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   11 hrs 21 mins      ████████████████████░░░░░   81.79% 
Image (svg)              1 hr 24 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.19% 
Other                    47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.68% 
TOML                     18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.2% 
Text                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

🔥 Editors: 
VS Code                  11 hrs 41 mins      █████████████████████░░░░   84.18% 
Figma                    1 hr 24 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.19% 
GIMP                     41 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.02% 
Terminal                 5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.61%

💻 Operating System: 
Mac                      13 hrs 53 mins      █████████████████████████   100.0%

```


 Last Updated on 17/09/2025 18:45:20 UTC
<!--END_SECTION:waka-->
