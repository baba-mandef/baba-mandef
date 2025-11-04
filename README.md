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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C871%20hrs%208%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     1 hr 13 mins        ████████░░░░░░░░░░░░░░░░░   33.96% 
Python                   1 hr 4 mins         ███████░░░░░░░░░░░░░░░░░░   30.09% 
Markdown                 37 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.53% 
Other                    27 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.87% 
Image (svg)              9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.43%

🔥 Editors: 
VS Code                  2 hrs 58 mins       ████████████████████░░░░░   82.7% 
Terminal                 15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.29% 
Notion                   11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.38% 
Figma                    9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.43% 
Notes                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

💻 Operating System: 
Mac                      3 hrs 35 mins       █████████████████████████   100.0%

```


 Last Updated on 04/11/2025 18:48:00 UTC
<!--END_SECTION:waka-->
