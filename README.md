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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C546%20hrs%2028%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 42 mins       ██████████████░░░░░░░░░░░   58.48% 
Python                   3 hrs 44 mins       ████████░░░░░░░░░░░░░░░░░   32.58% 
Gettext Catalog          30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.49% 
CSS                      15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.28% 
JSON                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.95%

🔥 Editors: 
VS Code                  11 hrs 29 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
2a7affc126b26b02f2edeb69d5 hrs 7 mins        ███████████░░░░░░░░░░░░░░   44.58% 
investioo                3 hrs 44 mins       ████████░░░░░░░░░░░░░░░░░   32.6% 
ekilibre                 2 hrs 14 mins       ████░░░░░░░░░░░░░░░░░░░░░   19.45% 
burnzzy-shop             8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.26% 
ishiro                   6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.97%

💻 Operating System: 
Linux                    11 hrs 29 mins      █████████████████████████   100.0%

```


 Last Updated on 23/02/2025 18:39:27 UTC
<!--END_SECTION:waka-->
