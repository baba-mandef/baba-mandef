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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C895%20hrs%2042%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   13 hrs 51 mins      ██████████████████████░░░   89.63% 
Image (svg)              47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.08% 
Other                    42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.53% 
TOML                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3% 
Text                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

🔥 Editors: 
VS Code                  13 hrs 58 mins      ██████████████████████░░░   90.37% 
Figma                    47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.08% 
GIMP                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.66% 
Terminal                 15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.71% 
Notion                   1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

💻 Operating System: 
Mac                      15 hrs 27 mins      █████████████████████████   100.0%

```


 Last Updated on 18/11/2025 18:49:49 UTC
<!--END_SECTION:waka-->
