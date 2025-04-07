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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C623%20hrs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1338-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 22 mins       ████████████░░░░░░░░░░░░░   49.22% 
Python                   3 hrs 58 mins       ███████░░░░░░░░░░░░░░░░░░   30.66% 
JavaScript               1 hr 14 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.53% 
Text                     42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.42% 
CSS                      38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.96%

🔥 Editors: 
VS Code                  12 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        7 hrs 15 mins       ██████████████░░░░░░░░░░░   56.01% 
api.checkupclimat.com    4 hrs 43 mins       █████████░░░░░░░░░░░░░░░░   36.48% 
solak                    51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.62% 
dist                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89%

💻 Operating System: 
Linux                    12 hrs 57 mins      █████████████████████████   100.0%

```


 Last Updated on 07/04/2025 18:43:13 UTC
<!--END_SECTION:waka-->
