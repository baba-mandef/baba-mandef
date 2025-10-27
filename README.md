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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C868%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 49 mins       ████████████████░░░░░░░░░   66.28% 
HTML                     56 mins             █████░░░░░░░░░░░░░░░░░░░░   22.2% 
Python                   26 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.47% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94% 
Git                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

🔥 Editors: 
GIMP                     1 hr 56 mins        ███████████░░░░░░░░░░░░░░   45.59% 
VS Code                  1 hr 26 mins        ████████░░░░░░░░░░░░░░░░░   33.72% 
Terminal                 36 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.25% 
Notion                   16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.45%

💻 Operating System: 
Mac                      4 hrs 16 mins       █████████████████████████   100.0%

```


 Last Updated on 27/10/2025 18:47:28 UTC
<!--END_SECTION:waka-->
