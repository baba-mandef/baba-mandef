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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C533%20hrs%2019%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   7 hrs 50 mins       █████████████░░░░░░░░░░░░   54.48% 
HTML                     5 hrs 39 mins       █████████░░░░░░░░░░░░░░░░   39.25% 
JavaScript               46 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.32% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.45% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

🔥 Editors: 
VS Code                  14 hrs 24 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 11 hrs 14 mins      ███████████████████░░░░░░   78.05% 
burnzzy-shop             1 hr 24 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.82% 
interlin                 58 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.82% 
investioo                36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.24% 
MULTI                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.06%

💻 Operating System: 
Linux                    14 hrs 24 mins      █████████████████████████   100.0%

```


 Last Updated on 13/02/2025 18:42:50 UTC
<!--END_SECTION:waka-->
