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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C538%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     7 hrs 51 mins       ████████████░░░░░░░░░░░░░   50.21% 
Python                   6 hrs 39 mins       ██████████░░░░░░░░░░░░░░░   42.51% 
JavaScript               46 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.9% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81% 
Dart                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.46%

🔥 Editors: 
VS Code                  15 hrs 39 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 8 hrs 50 mins       ██████████████░░░░░░░░░░░   56.39% 
interlin                 2 hrs 32 mins       ████░░░░░░░░░░░░░░░░░░░░░   16.2% 
2a7affc126b26b02f2edeb69d2 hrs 1 min         ███░░░░░░░░░░░░░░░░░░░░░░   12.98% 
investioo                1 hr                █░░░░░░░░░░░░░░░░░░░░░░░░   6.47% 
burnzzy-shop             51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.43%

💻 Operating System: 
Linux                    15 hrs 39 mins      █████████████████████████   100.0%

```


 Last Updated on 17/02/2025 18:41:31 UTC
<!--END_SECTION:waka-->
