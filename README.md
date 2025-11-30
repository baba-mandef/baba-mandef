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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C911%20hrs%2012%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 16 mins       █████████░░░░░░░░░░░░░░░░   37.63% 
Other                    4 hrs 4 mins        ███████░░░░░░░░░░░░░░░░░░   29.08% 
Python                   3 hrs 59 mins       ███████░░░░░░░░░░░░░░░░░░   28.55% 
CSS                      29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.49% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.98%

🔥 Editors: 
VS Code                  9 hrs 55 mins       █████████████████░░░░░░░░   70.82% 
Terminal                 3 hrs 16 mins       █████░░░░░░░░░░░░░░░░░░░░   23.41% 
GIMP                     47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.67% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

💻 Operating System: 
Mac                      14 hrs              █████████████████████████   100.0%

```


 Last Updated on 30/11/2025 18:45:48 UTC
<!--END_SECTION:waka-->
