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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C911%20hrs%2012%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 25 mins       ██████████░░░░░░░░░░░░░░░   41.21% 
Other                    4 hrs               ███████░░░░░░░░░░░░░░░░░░   30.41% 
Python                   3 hrs 7 mins        ██████░░░░░░░░░░░░░░░░░░░   23.77% 
CSS                      29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.71% 
Text                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74%

🔥 Editors: 
VS Code                  9 hrs 9 mins        █████████████████░░░░░░░░   69.5% 
Terminal                 3 hrs 12 mins       ██████░░░░░░░░░░░░░░░░░░░   24.39% 
GIMP                     47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.03% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

💻 Operating System: 
Mac                      13 hrs 10 mins      █████████████████████████   100.0%

```


 Last Updated on 02/12/2025 18:53:41 UTC
<!--END_SECTION:waka-->
