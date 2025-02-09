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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C517%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   7 hrs 57 mins       ███████████░░░░░░░░░░░░░░   46.5% 
HTML                     7 hrs 44 mins       ███████████░░░░░░░░░░░░░░   45.23% 
Bash                     37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.63% 
Text                     21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.11% 
JavaScript               19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.86%

🔥 Editors: 
VS Code                  17 hrs 7 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
burnzzy-shop             9 hrs 47 mins       ██████████████░░░░░░░░░░░   57.2% 
ges-emp                  4 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   25.84% 
interlin                 1 hr 26 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.38% 
investioo                36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.52% 
ekilibre                 30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.94%

💻 Operating System: 
Linux                    17 hrs 7 mins       █████████████████████████   100.0%

```


 Last Updated on 09/02/2025 18:38:50 UTC
<!--END_SECTION:waka-->
