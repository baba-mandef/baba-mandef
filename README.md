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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C876%20hrs%2036%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 39 mins       █████████░░░░░░░░░░░░░░░░   38.35% 
Other                    2 hrs 24 mins       ████████░░░░░░░░░░░░░░░░░   34.79% 
HTML                     1 hr 44 mins        ██████░░░░░░░░░░░░░░░░░░░   25.24% 
Image (svg)              5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.21% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

🔥 Editors: 
VS Code                  4 hrs 25 mins       ████████████████░░░░░░░░░   63.95% 
Notion                   1 hr 20 mins        ████░░░░░░░░░░░░░░░░░░░░░   19.41% 
Terminal                 42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.27% 
GIMP                     21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.11% 
Figma                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.21%

💻 Operating System: 
Mac                      6 hrs 55 mins       █████████████████████████   100.0%

```


 Last Updated on 10/11/2025 18:46:58 UTC
<!--END_SECTION:waka-->
