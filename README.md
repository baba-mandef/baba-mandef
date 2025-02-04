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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C501%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   11 hrs 55 mins      ██████████████░░░░░░░░░░░   57.51% 
HTML                     7 hrs 13 mins       ████████░░░░░░░░░░░░░░░░░   34.84% 
Text                     43 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.49% 
Bash                     32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.62% 
JavaScript               9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74%

🔥 Editors: 
VS Code                  20 hrs 44 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 9 hrs 19 mins       ███████████░░░░░░░░░░░░░░   44.99% 
ges-emp                  4 hrs 25 mins       █████░░░░░░░░░░░░░░░░░░░░   21.33% 
ekilibre                 3 hrs 25 mins       ████░░░░░░░░░░░░░░░░░░░░░   16.53% 
burnzzy-shop             2 hrs 22 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   11.43% 
investioo                54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.35%

💻 Operating System: 
Linux                    20 hrs 44 mins      █████████████████████████   100.0%

```


 Last Updated on 04/02/2025 18:41:47 UTC
<!--END_SECTION:waka-->
