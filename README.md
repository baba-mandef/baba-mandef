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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C550%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 32 mins       ██████████████░░░░░░░░░░░   59.18% 
Python                   3 hrs 35 mins       ████████░░░░░░░░░░░░░░░░░   32.53% 
Gettext Catalog          30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.66% 
CSS                      15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.37% 
JSON                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.99%

🔥 Editors: 
VS Code                  11 hrs 3 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
2a7affc126b26b02f2edeb69d5 hrs 13 mins       ███████████░░░░░░░░░░░░░░   47.29% 
investioo                2 hrs 45 mins       ██████░░░░░░░░░░░░░░░░░░░   24.95% 
ekilibre                 2 hrs 14 mins       █████░░░░░░░░░░░░░░░░░░░░   20.21% 
interlin                 38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.75% 
burnzzy-shop             6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.91%

💻 Operating System: 
Linux                    11 hrs 3 mins       █████████████████████████   100.0%

```


 Last Updated on 24/02/2025 18:43:25 UTC
<!--END_SECTION:waka-->
