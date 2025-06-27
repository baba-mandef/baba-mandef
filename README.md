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
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C706%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     8 hrs 43 mins       █████████████░░░░░░░░░░░░   53.66% 
Python                   4 hrs 48 mins       ███████░░░░░░░░░░░░░░░░░░   29.57% 
CSS                      1 hr 36 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.91% 
Gettext Catalog          22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.27% 
Other                    20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.07%

🔥 Editors: 
VS Code                  16 hrs 15 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    16 hrs 15 mins      █████████████████████████   100.0%

```


 Last Updated on 27/06/2025 18:47:57 UTC
<!--END_SECTION:waka-->
