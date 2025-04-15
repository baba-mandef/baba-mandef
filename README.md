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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C637%20hrs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     8 hrs 44 mins       █████████████████░░░░░░░░   71.21% 
Python                   2 hrs 27 mins       █████░░░░░░░░░░░░░░░░░░░░   20.03% 
JavaScript               37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.13% 
CSS                      24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.35% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

🔥 Editors: 
VS Code                  12 hrs 16 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        9 hrs 37 mins       ███████████████████░░░░░░   78.45% 
api.checkupclimat.com    2 hrs 24 mins       █████░░░░░░░░░░░░░░░░░░░░   19.63% 
crypo.netlify.app        7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.99% 
solak                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.92% 
trade                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    12 hrs 16 mins      █████████████████████████   100.0%

```


 Last Updated on 15/04/2025 18:44:21 UTC
<!--END_SECTION:waka-->
