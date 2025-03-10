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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C594%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     9 hrs 58 mins       █████████████░░░░░░░░░░░░   53.96% 
Python                   8 hrs 9 mins        ███████████░░░░░░░░░░░░░░   44.09% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.79% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.69% 
JavaScript               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21%

🔥 Editors: 
VS Code                  18 hrs 29 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
dreambigforinculsion     9 hrs 51 mins       █████████████░░░░░░░░░░░░   53.26% 
interlin                 5 hrs 41 mins       ███████░░░░░░░░░░░░░░░░░░   30.76% 
investioo                2 hrs 47 mins       ███░░░░░░░░░░░░░░░░░░░░░░   15.13% 
jago-welfare             7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.66% 
wuloevents-api           2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

💻 Operating System: 
Linux                    18 hrs 29 mins      █████████████████████████   100.0%

```


 Last Updated on 10/03/2025 18:43:12 UTC
<!--END_SECTION:waka-->
