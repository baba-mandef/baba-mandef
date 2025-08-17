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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C772%20hrs%2019%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 38 mins       ██████████████░░░░░░░░░░░   57.49% 
HTML                     5 hrs 49 mins       ████████░░░░░░░░░░░░░░░░░   34.72% 
CSS                      32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.18% 
Bash                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.69% 
TOML                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.59%

🔥 Editors: 
VS Code                  16 hrs 46 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      16 hrs 33 mins      ████████████████████████░   98.76% 
Linux                    12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.24%

```


 Last Updated on 17/08/2025 18:47:16 UTC
<!--END_SECTION:waka-->
