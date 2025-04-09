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
HTML                     6 hrs 51 mins       ███████████████░░░░░░░░░░   63.14% 
Python                   2 hrs 12 mins       █████░░░░░░░░░░░░░░░░░░░░   20.29% 
JavaScript               1 hr 9 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   10.58% 
CSS                      38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.92% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07%

🔥 Editors: 
VS Code                  10 hrs 52 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        6 hrs 24 mins       ██████████████░░░░░░░░░░░   58.91% 
api.checkupclimat.com    3 hrs 29 mins       ████████░░░░░░░░░░░░░░░░░   32.13% 
solak                    51 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.9% 
dist                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.06%

💻 Operating System: 
Linux                    10 hrs 52 mins      █████████████████████████   100.0%

```


 Last Updated on 09/04/2025 18:45:00 UTC
<!--END_SECTION:waka-->
