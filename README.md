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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C519%20hrs%2048%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     9 hrs 19 mins       ████████████░░░░░░░░░░░░░   48.57% 
Python                   8 hrs 39 mins       ███████████░░░░░░░░░░░░░░   45.16% 
JavaScript               55 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.79% 
Bash                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.91% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32%

🔥 Editors: 
VS Code                  19 hrs 11 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 9 hrs 5 mins        ███████████░░░░░░░░░░░░░░   47.35% 
burnzzy-shop             8 hrs 13 mins       ██████████░░░░░░░░░░░░░░░   42.89% 
interlin                 59 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.19% 
investioo                36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.14% 
MULTI                    16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.42%

💻 Operating System: 
Linux                    19 hrs 11 mins      █████████████████████████   100.0%

```


 Last Updated on 11/02/2025 18:41:45 UTC
<!--END_SECTION:waka-->
