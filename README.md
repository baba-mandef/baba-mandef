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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C623%20hrs%2030%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1338-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 48 mins       ███████████████████░░░░░░   79.48% 
CSS                      1 hr 3 mins         ███░░░░░░░░░░░░░░░░░░░░░░   12.28% 
Python                   27 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.26% 
JavaScript               14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.89% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

🔥 Editors: 
VS Code                  8 hrs 34 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
api.checkupclimat.com    4 hrs 22 mins       ████████████░░░░░░░░░░░░░   51.0% 
investioo-finance        3 hrs 18 mins       █████████░░░░░░░░░░░░░░░░   38.62% 
solak                    53 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.37%

💻 Operating System: 
Linux                    8 hrs 34 mins       █████████████████████████   100.0%

```


 Last Updated on 10/04/2025 18:43:26 UTC
<!--END_SECTION:waka-->
