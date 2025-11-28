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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C908%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    3 hrs 30 mins       █████████░░░░░░░░░░░░░░░░   36.29% 
HTML                     3 hrs 28 mins       █████████░░░░░░░░░░░░░░░░   35.96% 
Python                   2 hrs 31 mins       ██████░░░░░░░░░░░░░░░░░░░   26.12% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.41% 
Image (svg)              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

🔥 Editors: 
VS Code                  6 hrs 8 mins        ████████████████░░░░░░░░░   63.57% 
Terminal                 3 hrs 30 mins       █████████░░░░░░░░░░░░░░░░   36.29% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

💻 Operating System: 
Mac                      9 hrs 40 mins       █████████████████████████   100.0%

```


 Last Updated on 28/11/2025 18:46:39 UTC
<!--END_SECTION:waka-->
