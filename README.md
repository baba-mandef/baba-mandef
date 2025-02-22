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
HTML                     4 hrs 43 mins       ██████████████░░░░░░░░░░░   56.6% 
Python                   2 hrs 35 mins       ███████░░░░░░░░░░░░░░░░░░   31.1% 
Gettext Catalog          30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.17% 
CSS                      15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.14% 
JSON                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.31%

🔥 Editors: 
VS Code                  8 hrs 21 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                3 hrs 2 mins        █████████░░░░░░░░░░░░░░░░   36.38% 
2a7affc126b26b02f2edeb69d2 hrs 41 mins       ████████░░░░░░░░░░░░░░░░░   32.24% 
ekilibre                 2 hrs 14 mins       ██████░░░░░░░░░░░░░░░░░░░   26.75% 
burnzzy-shop             8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.74% 
ishiro                   6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.33%

💻 Operating System: 
Linux                    8 hrs 21 mins       █████████████████████████   100.0%

```


 Last Updated on 22/02/2025 18:39:45 UTC
<!--END_SECTION:waka-->
