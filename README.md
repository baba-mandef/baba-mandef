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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C981%20hrs%207%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 36 mins       █████████████████░░░░░░░░   68.8% 
Other                    1 hr 46 mins        █████░░░░░░░░░░░░░░░░░░░░   21.72% 
Image (svg)              23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.81% 
HTML                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.4% 
Bash                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.43%

🔥 Editors: 
VS Code                  5 hrs 59 mins       ██████████████████░░░░░░░   73.47% 
Terminal                 1 hr 15 mins        ███░░░░░░░░░░░░░░░░░░░░░░   15.45% 
Figma                    23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.81% 
GIMP                     20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.13% 
FileZilla                10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.1%

💻 Operating System: 
Mac                      8 hrs 9 mins        █████████████████████████   100.0%

```


 Last Updated on 30/01/2026 19:06:13 UTC
<!--END_SECTION:waka-->
