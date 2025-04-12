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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C626%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 53 mins       ████████████████████░░░░░   81.23% 
Python                   41 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.56% 
CSS                      24 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.65% 
JavaScript               15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.45% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  7 hrs 15 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        4 hrs 37 mins       ████████████████░░░░░░░░░   63.62% 
api.checkupclimat.com    2 hrs 24 mins       ████████░░░░░░░░░░░░░░░░░   33.21% 
crypo.netlify.app        7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.62% 
solak                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55%

💻 Operating System: 
Linux                    7 hrs 15 mins       █████████████████████████   100.0%

```


 Last Updated on 12/04/2025 18:41:43 UTC
<!--END_SECTION:waka-->
