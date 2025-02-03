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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C506%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 24 mins       ██████████████░░░░░░░░░░░   58.16% 
HTML                     5 hrs 40 mins       ████████░░░░░░░░░░░░░░░░░   35.06% 
Text                     34 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.52% 
Bash                     12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.33% 
JavaScript               9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.95%

🔥 Editors: 
VS Code                  16 hrs 10 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 9 hrs 32 mins       ██████████████░░░░░░░░░░░   58.95% 
ekilibre                 3 hrs 44 mins       █████░░░░░░░░░░░░░░░░░░░░   23.15% 
burnzzy-shop             1 hr 19 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.19% 
investioo                55 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.67% 
agri-pelle               26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.74%

💻 Operating System: 
Linux                    16 hrs 10 mins      █████████████████████████   100.0%

```


 Last Updated on 03/02/2025 18:40:25 UTC
<!--END_SECTION:waka-->
