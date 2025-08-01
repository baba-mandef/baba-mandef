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
                       'languages': ['Python', 'JS', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'English', 'French'],
                       'tools': ['Django', 'React', 'Flet', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C746%20hrs%2024%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 53 mins       ████████████████████░░░░░   82.57% 
HTML                     1 hr 39 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.84% 
Git Config               12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.8% 
Bash                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.61% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  11 hrs 59 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      11 hrs 47 mins      ████████████████████████░   98.45% 
Linux                    11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55%

```


 Last Updated on 01/08/2025 18:52:27 UTC
<!--END_SECTION:waka-->
