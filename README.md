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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C775%20hrs%2012%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   11 hrs 57 mins      ████████████████░░░░░░░░░   66.23% 
HTML                     4 hrs 51 mins       ██████░░░░░░░░░░░░░░░░░░░   26.91% 
CSS                      32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.96% 
Bash                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.57% 
TOML                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.48%

🔥 Editors: 
VS Code                  18 hrs 2 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      17 hrs 58 mins      █████████████████████████   99.62% 
Linux                    4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.38%

```


 Last Updated on 18/08/2025 18:51:20 UTC
<!--END_SECTION:waka-->
