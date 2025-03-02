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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C574%20hrs%2055%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   14 hrs 19 mins      ████████████░░░░░░░░░░░░░   49.17% 
HTML                     11 hrs 33 mins      ██████████░░░░░░░░░░░░░░░   39.67% 
JavaScript               1 hr 34 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.38% 
Bash                     39 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26% 
Text                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12%

🔥 Editors: 
VS Code                  29 hrs 7 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        13 hrs 21 mins      ███████████░░░░░░░░░░░░░░   45.83% 
wuloevents-api           9 hrs 42 mins       ████████░░░░░░░░░░░░░░░░░   33.33% 
interlin                 4 hrs 59 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.15% 
investioo                50 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.92% 
dist                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.42%

💻 Operating System: 
Linux                    29 hrs 7 mins       █████████████████████████   100.0%

```


 Last Updated on 02/03/2025 18:42:05 UTC
<!--END_SECTION:waka-->
