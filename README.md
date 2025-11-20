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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C895%20hrs%2042%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 54 mins       ███████████████████████░░   93.43% 
Image (svg)              19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.16% 
TOML                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.72% 
Text                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44% 
SQL                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.25%

🔥 Editors: 
VS Code                  5 hrs 59 mins       ███████████████████████░░   94.84% 
Figma                    19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.16%

💻 Operating System: 
Mac                      6 hrs 18 mins       █████████████████████████   100.0%

```


 Last Updated on 20/11/2025 18:49:25 UTC
<!--END_SECTION:waka-->
