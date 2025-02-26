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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C563%20hrs%2013%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 17 mins       ████████████░░░░░░░░░░░░░   50.47% 
HTML                     7 hrs 38 mins       ██████████░░░░░░░░░░░░░░░   41.55% 
Bash                     37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.37% 
Text                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.27% 
JavaScript               13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.22%

🔥 Editors: 
VS Code                  18 hrs 24 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
wuloevents-api           6 hrs 54 mins       █████████░░░░░░░░░░░░░░░░   37.51% 
interlin                 4 hrs 59 mins       ██████░░░░░░░░░░░░░░░░░░░   27.12% 
2a7affc126b26b02f2edeb69d3 hrs 41 mins       █████░░░░░░░░░░░░░░░░░░░░   20.03% 
ekilibre                 1 hr 47 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.69% 
investioo                1 hr 2 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.65%

💻 Operating System: 
Linux                    18 hrs 24 mins      █████████████████████████   100.0%

```


 Last Updated on 26/02/2025 18:43:17 UTC
<!--END_SECTION:waka-->
