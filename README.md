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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C386%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   18 hrs 58 mins      █████████████░░░░░░░░░░░░   54.29% 
HTML                     15 hrs 18 mins      ███████████░░░░░░░░░░░░░░   43.79% 
JavaScript               25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.19% 
Other                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.31% 
CSS                      5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.27%

🔥 Editors: 
VS Code                  34 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 23 hrs 30 mins      ████████████████░░░░░░░░░   67.25% 
investioo                11 hrs 6 mins       ████████░░░░░░░░░░░░░░░░░   31.76% 
MULTI                    19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.92% 
default                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07%

💻 Operating System: 
Linux                    34 hrs 57 mins      █████████████████████████   100.0%

```


 Last Updated on 10/01/2025 18:42:23 UTC
<!--END_SECTION:waka-->
