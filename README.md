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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C818%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   15 hrs 45 mins      ███████████░░░░░░░░░░░░░░   45.12% 
HTML                     12 hrs 59 mins      █████████░░░░░░░░░░░░░░░░   37.22% 
Other                    4 hrs 37 mins       ███░░░░░░░░░░░░░░░░░░░░░░   13.23% 
Image (svg)              50 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.43% 
CSS                      32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55%

🔥 Editors: 
VS Code                  29 hrs 45 mins      █████████████████████░░░░   85.24% 
Terminal                 2 hrs 44 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   7.87% 
Notion                   1 hr 1 min          ░░░░░░░░░░░░░░░░░░░░░░░░░   2.93% 
Figma                    50 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.43% 
GIMP                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.5%

💻 Operating System: 
Mac                      34 hrs 54 mins      █████████████████████████   100.0%

```


 Last Updated on 27/08/2025 18:44:24 UTC
<!--END_SECTION:waka-->
