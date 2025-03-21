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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C599%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 13 mins       ███████████████████░░░░░░   79.05% 
HTML                     41 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.97% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.63% 
JavaScript               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.32% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  4 hrs 4 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        3 hrs 48 mins       ███████████████████████░░   93.29% 
interlin                 10 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.45% 
dreambigforinculsion     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.26% 
wuloevents-api           1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81% 
ekilibre                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

💻 Operating System: 
Linux                    4 hrs 4 mins        █████████████████████████   100.0%

```


 Last Updated on 21/03/2025 18:43:52 UTC
<!--END_SECTION:waka-->
