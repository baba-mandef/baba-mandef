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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C471%20hrs%2059%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   17 hrs 38 mins      ████████████░░░░░░░░░░░░░   50.19% 
HTML                     16 hrs 13 mins      ███████████░░░░░░░░░░░░░░   46.17% 
Text                     48 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.3% 
JSON                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5% 
Git Config               9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.45%

🔥 Editors: 
VS Code                  35 hrs 8 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 32 hrs 11 mins      ███████████████████████░░   91.62% 
interlin                 2 hrs 23 mins       █░░░░░░░░░░░░░░░░░░░░░░░░   6.83% 
MULTI                    24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.19% 
suprek                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21% 
antek                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

💻 Operating System: 
Linux                    35 hrs 8 mins       █████████████████████████   100.0%

```


 Last Updated on 23/01/2025 18:41:57 UTC
<!--END_SECTION:waka-->
