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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C511%20hrs%2028%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     8 hrs 21 mins       ███████████░░░░░░░░░░░░░░   46.79% 
Python                   8 hrs 9 mins        ███████████░░░░░░░░░░░░░░   45.67% 
Bash                     37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.48% 
Text                     21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.03% 
JavaScript               18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.71%

🔥 Editors: 
VS Code                  17 hrs 52 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
burnzzy-shop             9 hrs 11 mins       ████████████░░░░░░░░░░░░░   51.4% 
ges-emp                  4 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   24.75% 
interlin                 3 hrs 15 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.27% 
ekilibre                 37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.51% 
abiodoun.dev             9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.86%

💻 Operating System: 
Linux                    17 hrs 52 mins      █████████████████████████   100.0%

```


 Last Updated on 06/02/2025 18:42:11 UTC
<!--END_SECTION:waka-->
