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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C594%20hrs%2039%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 35 mins       ████████████░░░░░░░░░░░░░   49.49% 
HTML                     4 hrs 5 mins        ███████████░░░░░░░░░░░░░░   44.02% 
JavaScript               26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.71% 
CSS                      6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.21% 
Bash                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.39%

🔥 Editors: 
VS Code                  9 hrs 16 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 5 hrs 41 mins       ███████████████░░░░░░░░░░   61.42% 
investioo                2 hrs 48 mins       ███████░░░░░░░░░░░░░░░░░░   30.19% 
abiodoun.dev             23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.3% 
wuloevents-api           22 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.09%

💻 Operating System: 
Linux                    9 hrs 16 mins       █████████████████████████   100.0%

```


 Last Updated on 13/03/2025 18:44:11 UTC
<!--END_SECTION:waka-->
