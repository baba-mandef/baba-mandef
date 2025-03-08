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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C592%20hrs%2021%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   6 hrs 49 mins       ████████████░░░░░░░░░░░░░   50.74% 
HTML                     6 hrs 27 mins       ████████████░░░░░░░░░░░░░   47.94% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.09% 
CSS                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12% 
Git                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

🔥 Editors: 
VS Code                  13 hrs 27 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
dreambigforinculsion     10 hrs 27 mins      ███████████████████░░░░░░   77.67% 
investioo                2 hrs 46 mins       █████░░░░░░░░░░░░░░░░░░░░   20.56% 
jago-welfare             10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.26% 
interlin                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5%

💻 Operating System: 
Linux                    13 hrs 27 mins      █████████████████████████   100.0%

```


 Last Updated on 08/03/2025 18:34:24 UTC
<!--END_SECTION:waka-->
