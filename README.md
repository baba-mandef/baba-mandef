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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C940%20hrs%2049%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 40 mins       █████████████░░░░░░░░░░░░   55.4% 
Python                   3 hrs 22 mins       ████████░░░░░░░░░░░░░░░░░   32.94% 
Other                    38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.33% 
JavaScript               15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.48% 
Image (svg)              12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.04%

🔥 Editors: 
VS Code                  9 hrs 23 mins       ███████████████████████░░   91.63% 
Terminal                 38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.33% 
Figma                    12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.04%

💻 Operating System: 
Mac                      10 hrs 14 mins      █████████████████████████   100.0%

```


 Last Updated on 24/12/2025 18:50:05 UTC
<!--END_SECTION:waka-->
