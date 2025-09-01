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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C821%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 48 mins       █████████░░░░░░░░░░░░░░░░   39.16% 
Python                   2 hrs 46 mins       █████████░░░░░░░░░░░░░░░░   38.7% 
HTML                     1 hr 13 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.01% 
Image (svg)              15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.6% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74%

🔥 Editors: 
VS Code                  4 hrs 9 mins        ██████████████░░░░░░░░░░░   58.04% 
Terminal                 1 hr 28 mins        █████░░░░░░░░░░░░░░░░░░░░   20.54% 
Notion                   1 hr 16 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.82% 
Figma                    15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.6%

💻 Operating System: 
Mac                      7 hrs 9 mins        █████████████████████████   100.0%

```


 Last Updated on 01/09/2025 18:44:22 UTC
<!--END_SECTION:waka-->
