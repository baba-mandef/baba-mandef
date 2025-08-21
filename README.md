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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C784%20hrs%2048%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   11 hrs 38 mins      ███████████████░░░░░░░░░░   60.3% 
HTML                     6 hrs 9 mins        ████████░░░░░░░░░░░░░░░░░   31.9% 
CSS                      43 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.74% 
Other                    20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.76% 
TOML                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.39%

🔥 Editors: 
VS Code                  18 hrs 56 mins      ████████████████████████░   98.09% 
Terminal                 13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.14% 
Figma                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56% 
Notion                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19% 
FileZilla                0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

💻 Operating System: 
Mac                      19 hrs 15 mins      █████████████████████████   99.72% 
Linux                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28%

```


 Last Updated on 21/08/2025 18:46:13 UTC
<!--END_SECTION:waka-->
