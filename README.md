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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C865%20hrs%2022%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 54 mins       █████████████████░░░░░░░░   67.96% 
HTML                     49 mins             ████░░░░░░░░░░░░░░░░░░░░░   19.44% 
Python                   29 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.37% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94% 
XML                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

🔥 Editors: 
GIMP                     1 hr 56 mins        ███████████░░░░░░░░░░░░░░   45.5% 
VS Code                  1 hr 22 mins        ████████░░░░░░░░░░░░░░░░░   32.04% 
Terminal                 40 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.0% 
Notion                   16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.46%

💻 Operating System: 
Mac                      4 hrs 16 mins       █████████████████████████   100.0%

```


 Last Updated on 25/10/2025 18:43:23 UTC
<!--END_SECTION:waka-->
