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
Python                   14 hrs 41 mins      ████████████░░░░░░░░░░░░░   50.4% 
HTML                     11 hrs 12 mins      █████████░░░░░░░░░░░░░░░░   38.44% 
JavaScript               1 hr 34 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.38% 
Bash                     39 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26% 
Text                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12%

🔥 Editors: 
VS Code                  29 hrs 8 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        13 hrs 21 mins      ███████████░░░░░░░░░░░░░░   45.82% 
wuloevents-api           9 hrs 42 mins       ████████░░░░░░░░░░░░░░░░░   33.32% 
interlin                 4 hrs 27 mins       ███░░░░░░░░░░░░░░░░░░░░░░   15.29% 
investioo                50 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.91% 
dreambigforinculsion     36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.07%

💻 Operating System: 
Linux                    29 hrs 8 mins       █████████████████████████   100.0%

```


 Last Updated on 03/03/2025 18:42:43 UTC
<!--END_SECTION:waka-->
