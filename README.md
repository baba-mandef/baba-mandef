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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C947%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 43 mins       ████████████░░░░░░░░░░░░░   50.77% 
HTML                     2 hrs 56 mins       ████████░░░░░░░░░░░░░░░░░   31.54% 
JavaScript               1 hr 30 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.19% 
Other                    8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.51%

🔥 Editors: 
VS Code                  9 hrs 9 mins        ████████████████████████░   98.49% 
Terminal                 8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.51%

💻 Operating System: 
Mac                      9 hrs 18 mins       █████████████████████████   100.0%

```


 Last Updated on 01/01/2026 18:50:26 UTC
<!--END_SECTION:waka-->
