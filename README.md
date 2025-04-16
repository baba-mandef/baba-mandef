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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C635%20hrs%2051%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     9 hrs 43 mins       █████████████████░░░░░░░░   68.04% 
Python                   2 hrs 27 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.21% 
JavaScript               1 hr 39 mins        ███░░░░░░░░░░░░░░░░░░░░░░   11.63% 
CSS                      24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.88% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.15%

🔥 Editors: 
VS Code                  14 hrs 17 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        11 hrs 30 mins      ████████████████████░░░░░   80.55% 
api.checkupclimat.com    2 hrs 24 mins       ████░░░░░░░░░░░░░░░░░░░░░   16.87% 
crypo.netlify.app        15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.78% 
solak                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.79% 
trade                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    14 hrs 17 mins      █████████████████████████   100.0%

```


 Last Updated on 16/04/2025 18:45:58 UTC
<!--END_SECTION:waka-->
