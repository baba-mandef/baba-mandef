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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C514%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   10 hrs 48 mins      ██████████████░░░░░░░░░░░   57.56% 
HTML                     6 hrs 43 mins       █████████░░░░░░░░░░░░░░░░   35.77% 
Bash                     37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.31% 
Text                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.97% 
JavaScript               12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.08%

🔥 Editors: 
VS Code                  18 hrs 47 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 7 hrs 32 mins       ██████████░░░░░░░░░░░░░░░   40.09% 
burnzzy-shop             5 hrs 47 mins       ███████░░░░░░░░░░░░░░░░░░   30.82% 
ges-emp                  4 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   23.54% 
ekilibre                 44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.94% 
abiodoun.dev             9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.82%

💻 Operating System: 
Linux                    18 hrs 47 mins      █████████████████████████   100.0%

```


 Last Updated on 05/02/2025 18:41:58 UTC
<!--END_SECTION:waka-->
