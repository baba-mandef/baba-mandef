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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C862%20hrs%2059%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 9 mins         ████████████████████████░   96.51% 
HTML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   2.62% 
Python                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.87%

🔥 Editors: 
GIMP                     39 mins             █████████████░░░░░░░░░░░░   55.49% 
Notion                   28 mins             ██████████░░░░░░░░░░░░░░░   39.95% 
VS Code                  2 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.82% 
Terminal                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74%

💻 Operating System: 
Mac                      1 hr 11 mins        █████████████████████████   100.0%

```


 Last Updated on 13/10/2025 18:45:19 UTC
<!--END_SECTION:waka-->
