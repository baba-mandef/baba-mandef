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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C594%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 52 mins       █████████████░░░░░░░░░░░░   52.07% 
HTML                     3 hrs 53 mins       ██████████░░░░░░░░░░░░░░░   41.5% 
JavaScript               26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.67% 
CSS                      6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.2% 
Bash                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.38%

🔥 Editors: 
VS Code                  9 hrs 22 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 5 hrs 41 mins       ███████████████░░░░░░░░░░   60.84% 
wuloevents-api           2 hrs               █████░░░░░░░░░░░░░░░░░░░░   21.49% 
investioo                1 hr 15 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.41% 
abiodoun.dev             23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.25%

💻 Operating System: 
Linux                    9 hrs 22 mins       █████████████████████████   100.0%

```


 Last Updated on 14/03/2025 18:42:40 UTC
<!--END_SECTION:waka-->
