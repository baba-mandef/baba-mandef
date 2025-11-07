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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C874%20hrs%2037%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     1 hr 59 mins        ████████░░░░░░░░░░░░░░░░░   35.24% 
Other                    1 hr 57 mins        ████████░░░░░░░░░░░░░░░░░   34.51% 
Python                   57 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.82% 
Markdown                 31 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.33% 
Image (svg)              12 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.64%

🔥 Editors: 
VS Code                  3 hrs 30 mins       ███████████████░░░░░░░░░░   61.77% 
Notion                   1 hr 20 mins        ██████░░░░░░░░░░░░░░░░░░░   23.69% 
GIMP                     21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.24% 
Terminal                 15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.46% 
Figma                    12 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.64%

💻 Operating System: 
Mac                      5 hrs 40 mins       █████████████████████████   100.0%

```


 Last Updated on 07/11/2025 18:44:46 UTC
<!--END_SECTION:waka-->
