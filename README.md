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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C534%20hrs%2012%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 20 mins       ████████████░░░░░░░░░░░░░   48.62% 
HTML                     7 hrs 47 mins       ███████████░░░░░░░░░░░░░░   45.38% 
JavaScript               46 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.47% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.38%

🔥 Editors: 
VS Code                  17 hrs 9 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 11 hrs 27 mins      ████████████████░░░░░░░░░   66.83% 
interlin                 2 hrs 32 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.8% 
2a7affc126b26b02f2edeb69d2 hrs 1 min         ███░░░░░░░░░░░░░░░░░░░░░░   11.85% 
burnzzy-shop             48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.7% 
MULTI                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.87%

💻 Operating System: 
Linux                    17 hrs 9 mins       █████████████████████████   100.0%

```


 Last Updated on 15/02/2025 18:38:36 UTC
<!--END_SECTION:waka-->
