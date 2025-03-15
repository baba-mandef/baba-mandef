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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C596%20hrs%2039%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 54 mins       ████████████░░░░░░░░░░░░░   47.8% 
HTML                     3 hrs 40 mins       ███████████░░░░░░░░░░░░░░   45.02% 
JavaScript               26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.35% 
CSS                      6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.38% 
Bash                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44%

🔥 Editors: 
VS Code                  8 hrs 10 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 5 hrs 41 mins       █████████████████░░░░░░░░   69.7% 
wuloevents-api           2 hrs 2 mins        ██████░░░░░░░░░░░░░░░░░░░   25.03% 
abiodoun.dev             23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.87% 
investioo                1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.39%

💻 Operating System: 
Linux                    8 hrs 10 mins       █████████████████████████   100.0%

```


 Last Updated on 15/03/2025 18:41:03 UTC
<!--END_SECTION:waka-->
