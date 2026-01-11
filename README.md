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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C969%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    3 hrs 57 mins       ████████████████████████░   96.55% 
HTML                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.45%

🔥 Editors: 
GIMP                     3 hrs 2 mins        ██████████████████░░░░░░░   74.0% 
Terminal                 42 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.13% 
Notion                   13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.42% 
VS Code                  8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.45%

💻 Operating System: 
Mac                      4 hrs 6 mins        █████████████████████████   100.0%

```


 Last Updated on 11/01/2026 18:49:02 UTC
<!--END_SECTION:waka-->
