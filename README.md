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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C748%20hrs%2027%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 6 mins        ███████████████████████░░   94.26% 
TOML                     16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.95% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44% 
Text                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34% 
HTML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
VS Code                  5 hrs 25 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      5 hrs 19 mins       ████████████████████████░   98.17% 
Linux                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.83%

```


 Last Updated on 07/08/2025 18:54:46 UTC
<!--END_SECTION:waka-->
