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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C585%20hrs%2038%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   14 hrs 7 mins       ████████████░░░░░░░░░░░░░   48.34% 
HTML                     12 hrs 25 mins      ██████████░░░░░░░░░░░░░░░   42.52% 
JavaScript               1 hr 34 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.36% 
Text                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.1% 
CSS                      11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.64%

🔥 Editors: 
VS Code                  29 hrs 13 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        13 hrs 22 mins      ███████████░░░░░░░░░░░░░░   45.75% 
wuloevents-api           7 hrs 42 mins       ██████░░░░░░░░░░░░░░░░░░░   26.38% 
dreambigforinculsion     5 hrs 17 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.12% 
interlin                 1 hr 45 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.0% 
investioo                52 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.98%

💻 Operating System: 
Linux                    29 hrs 13 mins      █████████████████████████   100.0%

```


 Last Updated on 04/03/2025 18:44:29 UTC
<!--END_SECTION:waka-->
