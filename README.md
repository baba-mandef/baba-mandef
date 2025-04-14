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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C632%20hrs%2026%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     8 hrs 44 mins       ██████████████████░░░░░░░   73.42% 
Python                   2 hrs 27 mins       █████░░░░░░░░░░░░░░░░░░░░   20.69% 
CSS                      24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.46% 
JavaScript               15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.2% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

🔥 Editors: 
VS Code                  11 hrs 54 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        9 hrs 15 mins       ███████████████████░░░░░░   77.79% 
api.checkupclimat.com    2 hrs 24 mins       █████░░░░░░░░░░░░░░░░░░░░   20.25% 
crypo.netlify.app        7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.02% 
solak                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94%

💻 Operating System: 
Linux                    11 hrs 54 mins      █████████████████████████   100.0%

```


 Last Updated on 14/04/2025 18:45:48 UTC
<!--END_SECTION:waka-->
