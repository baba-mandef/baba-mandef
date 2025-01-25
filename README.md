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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C482%20hrs%2042%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   16 hrs 12 mins      █████████████░░░░░░░░░░░░   53.94% 
HTML                     11 hrs 33 mins      █████████░░░░░░░░░░░░░░░░   38.47% 
JSON                     53 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.97% 
Text                     44 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.49% 
CSS                      24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.39%

🔥 Editors: 
VS Code                  30 hrs 2 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 23 hrs 6 mins       ███████████████████░░░░░░   76.92% 
interlin                 6 hrs 23 mins       █████░░░░░░░░░░░░░░░░░░░░   21.29% 
suprek                   14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.82% 
antek                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.54% 
MULTI                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28%

💻 Operating System: 
Linux                    30 hrs 2 mins       █████████████████████████   100.0%

```


 Last Updated on 25/01/2025 18:38:16 UTC
<!--END_SECTION:waka-->
