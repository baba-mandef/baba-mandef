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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C534%20hrs%2019%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 59 mins       ████████████░░░░░░░░░░░░░   50.83% 
HTML                     7 hrs 39 mins       ██████████░░░░░░░░░░░░░░░   43.35% 
JavaScript               46 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.34% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.72% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.37%

🔥 Editors: 
VS Code                  17 hrs 41 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 11 hrs 28 mins      ████████████████░░░░░░░░░   64.89% 
interlin                 2 hrs 35 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.67% 
2a7affc126b26b02f2edeb69d1 hr 54 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.82% 
burnzzy-shop             48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.56% 
investioo                36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.46%

💻 Operating System: 
Linux                    17 hrs 41 mins      █████████████████████████   100.0%

```


 Last Updated on 14/02/2025 18:41:38 UTC
<!--END_SECTION:waka-->
