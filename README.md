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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C313%20hrs%207%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 21 mins       █████████████░░░░░░░░░░░░   52.6% 
HTML                     7 hrs 17 mins       ███████████░░░░░░░░░░░░░░   45.97% 
Text                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.95% 
JavaScript               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32% 
CSS                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

🔥 Editors: 
VS Code                  15 hrs 52 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 8 hrs               ████████████░░░░░░░░░░░░░   50.42% 
investioo                7 hrs 22 mins       ███████████░░░░░░░░░░░░░░   46.43% 
default                  30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15%

💻 Operating System: 
Linux                    15 hrs 52 mins      █████████████████████████   100.0%

```


 Last Updated on 25/12/2024 18:40:51 UTC
<!--END_SECTION:waka-->
