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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C391%20hrs%2058%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   18 hrs 4 mins       ██████████████░░░░░░░░░░░   56.86% 
HTML                     13 hrs 4 mins       ██████████░░░░░░░░░░░░░░░   41.16% 
JavaScript               25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.34% 
Other                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34% 
CSS                      5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3%

🔥 Editors: 
VS Code                  31 hrs 46 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 20 hrs 23 mins      ████████████████░░░░░░░░░   64.17% 
investioo                11 hrs 2 mins       ████████░░░░░░░░░░░░░░░░░   34.75% 
MULTI                    19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.01% 
default                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

💻 Operating System: 
Linux                    31 hrs 46 mins      █████████████████████████   100.0%

```


 Last Updated on 09/01/2025 18:43:16 UTC
<!--END_SECTION:waka-->
