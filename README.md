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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C539%20hrs%2058%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 3 mins        ██████████████░░░░░░░░░░░   58.64% 
Python                   3 hrs 4 mins        ███████░░░░░░░░░░░░░░░░░░   29.77% 
Gettext Catalog          30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.99% 
CSS                      19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.16% 
JSON                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.29%

🔥 Editors: 
VS Code                  10 hrs 19 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
2a7affc126b26b02f2edeb69d3 hrs 43 mins       █████████░░░░░░░░░░░░░░░░   36.08% 
investioo                2 hrs 52 mins       ███████░░░░░░░░░░░░░░░░░░   27.81% 
interlin                 2 hrs 33 mins       ██████░░░░░░░░░░░░░░░░░░░   24.8% 
ekilibre                 40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.58% 
burnzzy-shop             8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.41%

💻 Operating System: 
Linux                    10 hrs 19 mins      █████████████████████████   100.0%

```


 Last Updated on 20/02/2025 18:42:41 UTC
<!--END_SECTION:waka-->
