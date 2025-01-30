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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C499%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   12 hrs 44 mins      █████████████░░░░░░░░░░░░   51.95% 
HTML                     9 hrs 21 mins       █████████░░░░░░░░░░░░░░░░   38.13% 
JSON                     1 hr 5 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   4.43% 
Text                     39 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.68% 
CSS                      21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.48%

🔥 Editors: 
VS Code                  24 hrs 31 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 10 hrs 46 mins      ███████████░░░░░░░░░░░░░░   43.94% 
ekilibre                 10 hrs 39 mins      ██████████░░░░░░░░░░░░░░░   43.46% 
investioo                2 hrs 19 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   9.48% 
agri-pelle               26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.81% 
suprek                   12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.88%

💻 Operating System: 
Linux                    24 hrs 31 mins      █████████████████████████   100.0%

```


 Last Updated on 30/01/2025 18:41:14 UTC
<!--END_SECTION:waka-->
