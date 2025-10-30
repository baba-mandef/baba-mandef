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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C868%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 33 mins       █████████████████░░░░░░░░   69.74% 
HTML                     33 mins             ███░░░░░░░░░░░░░░░░░░░░░░   15.15% 
Python                   29 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.24% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.1% 
TOML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.53%

🔥 Editors: 
GIMP                     1 hr 56 mins        █████████████░░░░░░░░░░░░   53.13% 
VS Code                  1 hr 6 mins         ███████░░░░░░░░░░░░░░░░░░   30.26% 
Terminal                 36 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.61%

💻 Operating System: 
Mac                      3 hrs 39 mins       █████████████████████████   100.0%

```


 Last Updated on 30/10/2025 18:48:11 UTC
<!--END_SECTION:waka-->
