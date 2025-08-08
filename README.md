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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C750%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 39 mins       ███████████████████████░░   94.43% 
TOML                     17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15% 
Git                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26% 
Text                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

🔥 Editors: 
VS Code                  9 hrs 9 mins        █████████████████████████   100.0%

💻 Operating System: 
Mac                      9 hrs 3 mins        ████████████████████████░   98.92% 
Linux                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.08%

```


 Last Updated on 08/08/2025 18:50:04 UTC
<!--END_SECTION:waka-->
