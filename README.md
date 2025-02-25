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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C557%20hrs%2024%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     7 hrs 33 mins       ██████████████░░░░░░░░░░░   58.91% 
Python                   4 hrs 20 mins       ████████░░░░░░░░░░░░░░░░░   33.88% 
Bash                     30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.97% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.16% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.96%

🔥 Editors: 
VS Code                  12 hrs 49 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
2a7affc126b26b02f2edeb69d4 hrs 32 mins       ████████░░░░░░░░░░░░░░░░░   35.42% 
interlin                 3 hrs 18 mins       ██████░░░░░░░░░░░░░░░░░░░   25.76% 
ekilibre                 2 hrs 6 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.4% 
wuloevents-api           1 hr 59 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.58% 
investioo                52 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.82%

💻 Operating System: 
Linux                    12 hrs 49 mins      █████████████████████████   100.0%

```


 Last Updated on 25/02/2025 18:43:34 UTC
<!--END_SECTION:waka-->
