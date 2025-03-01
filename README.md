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
Python                   15 hrs 28 mins      ████████████░░░░░░░░░░░░░   47.94% 
HTML                     13 hrs 32 mins      ██████████░░░░░░░░░░░░░░░   41.99% 
JavaScript               1 hr 33 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.84% 
Bash                     39 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.04% 
Text                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.01%

🔥 Editors: 
VS Code                  32 hrs 15 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        13 hrs 21 mins      ██████████░░░░░░░░░░░░░░░   41.38% 
wuloevents-api           9 hrs 42 mins       ███████░░░░░░░░░░░░░░░░░░   30.09% 
interlin                 4 hrs 59 mins       ███░░░░░░░░░░░░░░░░░░░░░░   15.47% 
2a7affc126b26b02f2edeb69d2 hrs 32 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   7.85% 
investioo                1 hr 33 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.82%

💻 Operating System: 
Linux                    32 hrs 15 mins      █████████████████████████   100.0%

```


 Last Updated on 01/03/2025 18:40:24 UTC
<!--END_SECTION:waka-->
