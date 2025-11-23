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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C897%20hrs%2019%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 5 mins        █████████████░░░░░░░░░░░░   54.99% 
Other                    1 hr 26 mins        █████████░░░░░░░░░░░░░░░░   37.85% 
Image (svg)              15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.96% 
TOML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

🔥 Editors: 
VS Code                  2 hrs 6 mins        █████████████░░░░░░░░░░░░   55.18% 
Terminal                 1 hr 26 mins        █████████░░░░░░░░░░░░░░░░   37.85% 
Figma                    15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.96%

💻 Operating System: 
Mac                      3 hrs 48 mins       █████████████████████████   100.0%

```


 Last Updated on 23/11/2025 18:45:09 UTC
<!--END_SECTION:waka-->
