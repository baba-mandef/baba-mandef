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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C733%20hrs%206%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 15 mins       ███████████████████████░░   92.04% 
Text                     14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.25% 
Bash                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.29% 
HTML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

🔥 Editors: 
VS Code                  5 hrs 42 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      5 hrs 31 mins       ████████████████████████░   96.73% 
Linux                    11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.27%

```


 Last Updated on 26/07/2025 18:48:59 UTC
<!--END_SECTION:waka-->
