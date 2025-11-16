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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C893%20hrs%2025%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   13 hrs 41 mins      ████████████████████░░░░░   82.15% 
Other                    1 hr 10 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.05% 
Image (svg)              32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23% 
JavaScript               29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.98% 
JSON                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.01%

🔥 Editors: 
VS Code                  14 hrs 57 mins      ██████████████████████░░░   89.72% 
Terminal                 44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.42% 
Figma                    32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23% 
GIMP                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.46% 
Notion                   1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

💻 Operating System: 
Mac                      16 hrs 40 mins      █████████████████████████   100.0%

```


 Last Updated on 16/11/2025 18:44:16 UTC
<!--END_SECTION:waka-->
