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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C770%20hrs%2023%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   7 hrs 5 mins        ████████████░░░░░░░░░░░░░   50.55% 
HTML                     5 hrs 48 mins       ██████████░░░░░░░░░░░░░░░   41.46% 
CSS                      20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.49% 
Bash                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.02% 
TOML                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.9%

🔥 Editors: 
VS Code                  14 hrs 1 min        █████████████████████████   100.0%

💻 Operating System: 
Mac                      13 hrs 48 mins      ████████████████████████░   98.52% 
Linux                    12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.48%

```


 Last Updated on 16/08/2025 18:45:44 UTC
<!--END_SECTION:waka-->
