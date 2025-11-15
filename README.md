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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C889%20hrs%2017%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   12 hrs 58 mins      ████████████████████░░░░░   81.44% 
Other                    1 hr 13 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.72% 
JavaScript               29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.11% 
Image (svg)              29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.04% 
JSON                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.1%

🔥 Editors: 
VS Code                  14 hrs 12 mins      ██████████████████████░░░   89.24% 
Terminal                 47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.97% 
Figma                    29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.04% 
GIMP                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.58% 
Notion                   1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

💻 Operating System: 
Mac                      15 hrs 55 mins      █████████████████████████   100.0%

```


 Last Updated on 15/11/2025 18:43:52 UTC
<!--END_SECTION:waka-->
