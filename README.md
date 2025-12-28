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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C943%20hrs%2050%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     1 hr 13 mins        ██████████░░░░░░░░░░░░░░░   42.23% 
Python                   1 hr 4 mins         █████████░░░░░░░░░░░░░░░░   37.27% 
Other                    34 mins             █████░░░░░░░░░░░░░░░░░░░░   19.87% 
JavaScript               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.64%

🔥 Editors: 
VS Code                  2 hrs 18 mins       ████████████████████░░░░░   80.13% 
Terminal                 34 mins             █████░░░░░░░░░░░░░░░░░░░░   19.87%

💻 Operating System: 
Mac                      2 hrs 53 mins       █████████████████████████   100.0%

```


 Last Updated on 28/12/2025 18:49:16 UTC
<!--END_SECTION:waka-->
