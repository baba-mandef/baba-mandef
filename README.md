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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C580%20hrs%2024%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     13 hrs 36 mins      ████████████░░░░░░░░░░░░░   49.1% 
Python                   12 hrs              ██████████░░░░░░░░░░░░░░░   43.37% 
JavaScript               1 hr 20 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.85% 
Text                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.86% 
CSS                      11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.68%

🔥 Editors: 
VS Code                  27 hrs 42 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        13 hrs 22 mins      ████████████░░░░░░░░░░░░░   48.28% 
dreambigforinculsion     10 hrs 27 mins      █████████░░░░░░░░░░░░░░░░   37.74% 
wuloevents-api           2 hrs 48 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   10.13% 
investioo                42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.55% 
jago-welfare             10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.61%

💻 Operating System: 
Linux                    27 hrs 42 mins      █████████████████████████   100.0%

```


 Last Updated on 05/03/2025 18:44:31 UTC
<!--END_SECTION:waka-->
