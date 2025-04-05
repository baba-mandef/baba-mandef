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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C622%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1338-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 22 mins       ████████████░░░░░░░░░░░░░   48.29% 
Python                   4 hrs 13 mins       ████████░░░░░░░░░░░░░░░░░   31.97% 
JavaScript               1 hr 14 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.35% 
Text                     42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.32% 
CSS                      38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.87%

🔥 Editors: 
VS Code                  13 hrs 12 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        7 hrs 30 mins       ██████████████░░░░░░░░░░░   56.84% 
api.checkupclimat.com    4 hrs 43 mins       █████████░░░░░░░░░░░░░░░░   35.79% 
solak                    51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.5% 
dist                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.87%

💻 Operating System: 
Linux                    13 hrs 12 mins      █████████████████████████   100.0%

```


 Last Updated on 05/04/2025 18:41:12 UTC
<!--END_SECTION:waka-->
