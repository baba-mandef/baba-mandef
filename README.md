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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C615%20hrs%2030%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1338-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 51 mins       ████████████░░░░░░░░░░░░░   47.55% 
HTML                     1 hr 41 mins        ███████░░░░░░░░░░░░░░░░░░   28.24% 
Text                     42 mins             ███░░░░░░░░░░░░░░░░░░░░░░   11.73% 
CSS                      36 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.23% 
JavaScript               6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.82%

🔥 Editors: 
VS Code                  5 hrs 59 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           2 hrs 23 mins       ██████████░░░░░░░░░░░░░░░   39.85% 
investioo-finance        2 hrs 21 mins       █████████░░░░░░░░░░░░░░░░   39.29% 
api.checkupclimat.com    1 hr 14 mins        █████░░░░░░░░░░░░░░░░░░░░   20.61% 
seomy                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.25%

💻 Operating System: 
Linux                    5 hrs 59 mins       █████████████████████████   100.0%

```


 Last Updated on 02/04/2025 18:45:19 UTC
<!--END_SECTION:waka-->
