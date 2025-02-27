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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C566%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   12 hrs 39 mins      ████████████░░░░░░░░░░░░░   51.17% 
HTML                     10 hrs 10 mins      ██████████░░░░░░░░░░░░░░░   41.12% 
Bash                     37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.51% 
JavaScript               30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.04% 
Text                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94%

🔥 Editors: 
VS Code                  24 hrs 43 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
wuloevents-api           9 hrs 42 mins       █████████░░░░░░░░░░░░░░░░   39.27% 
interlin                 4 hrs 59 mins       █████░░░░░░░░░░░░░░░░░░░░   20.19% 
investioo-finance        3 hrs 39 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.78% 
2a7affc126b26b02f2edeb69d3 hrs 30 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.22% 
ekilibre                 1 hr 47 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.22%

💻 Operating System: 
Linux                    24 hrs 43 mins      █████████████████████████   100.0%

```


 Last Updated on 27/02/2025 18:43:40 UTC
<!--END_SECTION:waka-->
