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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C472%20hrs%204%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   24 hrs 1 min        ████████████░░░░░░░░░░░░░   51.34% 
HTML                     21 hrs 22 mins      ███████████░░░░░░░░░░░░░░   45.69% 
Text                     48 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.72% 
JavaScript               19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.68% 
JSON                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.38%

🔥 Editors: 
VS Code                  46 hrs 47 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 44 hrs 50 mins      ████████████████████████░   95.83% 
interlin                 1 hr 22 mins        ░░░░░░░░░░░░░░░░░░░░░░░░░   2.94% 
MULTI                    30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.08% 
suprek                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

💻 Operating System: 
Linux                    46 hrs 47 mins      █████████████████████████   100.0%

```


 Last Updated on 22/01/2025 18:42:39 UTC
<!--END_SECTION:waka-->
