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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C878%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 9 mins        █████████░░░░░░░░░░░░░░░░   37.9% 
HTML                     1 hr 58 mins        ████████░░░░░░░░░░░░░░░░░   34.75% 
Python                   1 hr 27 mins        ██████░░░░░░░░░░░░░░░░░░░   25.66% 
Image (svg)              5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.47% 
Markdown                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

🔥 Editors: 
VS Code                  3 hrs 27 mins       ███████████████░░░░░░░░░░   60.56% 
Notion                   1 hr 20 mins        ██████░░░░░░░░░░░░░░░░░░░   23.56% 
Terminal                 27 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.01% 
GIMP                     21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.2% 
Figma                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.47%

💻 Operating System: 
Mac                      5 hrs 42 mins       █████████████████████████   100.0%

```


 Last Updated on 09/11/2025 18:42:38 UTC
<!--END_SECTION:waka-->
