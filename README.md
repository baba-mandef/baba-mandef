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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C942%20hrs%2029%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 29 mins       ███████████████░░░░░░░░░░   61.13% 
Python                   2 hrs 17 mins       ██████░░░░░░░░░░░░░░░░░░░   25.57% 
Other                    38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.22% 
JavaScript               15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.83% 
Image (svg)              12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.32%

🔥 Editors: 
VS Code                  8 hrs 7 mins        ██████████████████████░░░   90.46% 
Terminal                 38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.22% 
Figma                    12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.32%

💻 Operating System: 
Mac                      8 hrs 59 mins       █████████████████████████   100.0%

```


 Last Updated on 25/12/2025 18:49:49 UTC
<!--END_SECTION:waka-->
