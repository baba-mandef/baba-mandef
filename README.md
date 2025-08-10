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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C758%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   10 hrs 34 mins      ███████████████████████░░   92.73% 
Markdown                 28 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.21% 
Git                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.57% 
TOML                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.53% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.46%

🔥 Editors: 
VS Code                  11 hrs 23 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      11 hrs 18 mins      ████████████████████████░   99.27% 
Linux                    4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.73%

```


 Last Updated on 10/08/2025 18:47:11 UTC
<!--END_SECTION:waka-->
