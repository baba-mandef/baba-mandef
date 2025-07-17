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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C731%20hrs%2038%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
JavaScript               7 hrs 14 mins       ███████████████░░░░░░░░░░   63.3% 
Python                   2 hrs 38 mins       █████░░░░░░░░░░░░░░░░░░░░   23.11% 
HTML                     1 hr 14 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.81% 
Text                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.35% 
TOML                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.41%

🔥 Editors: 
VS Code                  11 hrs 26 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    11 hrs 26 mins      █████████████████████████   100.0%

```


 Last Updated on 17/07/2025 18:52:19 UTC
<!--END_SECTION:waka-->
