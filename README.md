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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C483%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   15 hrs 40 mins      █████████████░░░░░░░░░░░░   52.31% 
HTML                     11 hrs 36 mins      █████████░░░░░░░░░░░░░░░░   38.73% 
JSON                     1 hr 15 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.22% 
Text                     44 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.49% 
CSS                      24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.39%

🔥 Editors: 
VS Code                  29 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 21 hrs 59 mins      ██████████████████░░░░░░░   73.42% 
interlin                 6 hrs 26 mins       █████░░░░░░░░░░░░░░░░░░░░   21.48% 
investioo                1 hr 4 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   3.6% 
suprek                   14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.83% 
antek                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.54%

💻 Operating System: 
Linux                    29 hrs 57 mins      █████████████████████████   100.0%

```


 Last Updated on 26/01/2025 18:39:36 UTC
<!--END_SECTION:waka-->
