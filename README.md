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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C874%20hrs%2037%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     1 hr 56 mins        ████████░░░░░░░░░░░░░░░░░   34.48% 
Other                    1 hr 44 mins        ███████░░░░░░░░░░░░░░░░░░   31.01% 
Python                   1 hr 5 mins         ████░░░░░░░░░░░░░░░░░░░░░   19.23% 
Markdown                 37 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.17% 
Image (svg)              11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.41%

🔥 Editors: 
VS Code                  3 hrs 41 mins       ████████████████░░░░░░░░░   65.59% 
Notion                   1 hr 15 mins        █████░░░░░░░░░░░░░░░░░░░░   22.43% 
Terminal                 17 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.19% 
Figma                    11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.41% 
GIMP                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.26%

💻 Operating System: 
Mac                      5 hrs 38 mins       █████████████████████████   100.0%

```


 Last Updated on 05/11/2025 18:48:01 UTC
<!--END_SECTION:waka-->
