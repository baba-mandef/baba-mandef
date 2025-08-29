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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C819%20hrs%2042%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 51 mins       ████████████░░░░░░░░░░░░░   48.08% 
HTML                     5 hrs 48 mins       ███████░░░░░░░░░░░░░░░░░░   28.27% 
Other                    3 hrs 54 mins       ████░░░░░░░░░░░░░░░░░░░░░   19.05% 
Image (svg)              42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.49% 
CSS                      5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.47%

🔥 Editors: 
VS Code                  16 hrs 8 mins       ███████████████████░░░░░░   78.64% 
Terminal                 2 hrs 32 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.38% 
Figma                    42 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.49% 
Notion                   35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.91% 
GIMP                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.53%

💻 Operating System: 
Mac                      20 hrs 31 mins      █████████████████████████   100.0%

```


 Last Updated on 29/08/2025 18:43:30 UTC
<!--END_SECTION:waka-->
