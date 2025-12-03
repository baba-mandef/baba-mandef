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

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 14 mins       ███████████░░░░░░░░░░░░░░   44.86% 
Other                    3 hrs 12 mins       ██████░░░░░░░░░░░░░░░░░░░   27.4% 
Python                   2 hrs 38 mins       █████░░░░░░░░░░░░░░░░░░░░   22.63% 
CSS                      29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.18% 
Text                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.83%

🔥 Editors: 
VS Code                  8 hrs 28 mins       ██████████████████░░░░░░░   72.6% 
Terminal                 2 hrs 24 mins       █████░░░░░░░░░░░░░░░░░░░░   20.61% 
GIMP                     47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.8%

💻 Operating System: 
Mac                      11 hrs 41 mins      █████████████████████████   100.0%

```


 Last Updated on 03/12/2025 18:52:02 UTC
<!--END_SECTION:waka-->
