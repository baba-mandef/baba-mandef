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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C376%20hrs%201%20min-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   12 hrs 12 mins      ██████████████░░░░░░░░░░░   56.04% 
HTML                     9 hrs 24 mins       ██████████░░░░░░░░░░░░░░░   43.18% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.25% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21%

🔥 Editors: 
VS Code                  21 hrs 47 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                16 hrs 53 mins      ███████████████████░░░░░░   77.53% 
ekilibre                 4 hrs 50 mins       █████░░░░░░░░░░░░░░░░░░░░   22.23% 
hudim                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23%

💻 Operating System: 
Linux                    21 hrs 47 mins      █████████████████████████   100.0%

```


 Last Updated on 06/01/2025 18:42:30 UTC
<!--END_SECTION:waka-->
