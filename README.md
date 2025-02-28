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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C574%20hrs%2028%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   14 hrs 22 mins      █████████████░░░░░░░░░░░░   54.85% 
HTML                     9 hrs 55 mins       █████████░░░░░░░░░░░░░░░░   37.87% 
Bash                     37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.37% 
JavaScript               30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.93% 
Text                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89%

🔥 Editors: 
VS Code                  26 hrs 11 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
wuloevents-api           9 hrs 42 mins       █████████░░░░░░░░░░░░░░░░   37.06% 
investioo-finance        5 hrs 12 mins       █████░░░░░░░░░░░░░░░░░░░░   19.89% 
interlin                 4 hrs 59 mins       ████░░░░░░░░░░░░░░░░░░░░░   19.05% 
2a7affc126b26b02f2edeb69d3 hrs 15 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.44% 
ekilibre                 1 hr 47 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.81%

💻 Operating System: 
Linux                    26 hrs 11 mins      █████████████████████████   100.0%

```


 Last Updated on 28/02/2025 18:43:15 UTC
<!--END_SECTION:waka-->
