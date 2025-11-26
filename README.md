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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C899%20hrs%2034%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 40 mins       █████████████░░░░░░░░░░░░   52.75% 
Python                   1 hr 26 mins        ███████░░░░░░░░░░░░░░░░░░   28.34% 
HTML                     53 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.71% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.79% 
Image (svg)              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28%

🔥 Editors: 
Terminal                 2 hrs 40 mins       █████████████░░░░░░░░░░░░   52.75% 
VS Code                  2 hrs 22 mins       ███████████░░░░░░░░░░░░░░   46.98% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28%

💻 Operating System: 
Mac                      5 hrs 4 mins        █████████████████████████   100.0%

```


 Last Updated on 26/11/2025 18:45:55 UTC
<!--END_SECTION:waka-->
