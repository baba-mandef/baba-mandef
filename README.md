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
HTML                     7 hrs 14 mins       ███████████████░░░░░░░░░░   60.05% 
Python                   3 hrs 6 mins        ██████░░░░░░░░░░░░░░░░░░░   25.73% 
CSS                      1 hr 7 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   9.37% 
Gettext Catalog          22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.06% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5%

🔥 Editors: 
VS Code                  12 hrs 3 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    12 hrs 3 mins       █████████████████████████   100.0%

```


 Last Updated on 01/07/2025 18:47:54 UTC
<!--END_SECTION:waka-->
