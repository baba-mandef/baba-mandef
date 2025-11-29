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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C909%20hrs%2035%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 59 mins       ████████░░░░░░░░░░░░░░░░░   34.9% 
HTML                     3 hrs 47 mins       ████████░░░░░░░░░░░░░░░░░   33.07% 
Other                    3 hrs 29 mins       ███████░░░░░░░░░░░░░░░░░░   30.51% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.2% 
Markdown                 1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.15%

🔥 Editors: 
VS Code                  7 hrs 56 mins       █████████████████░░░░░░░░   69.37% 
Terminal                 3 hrs 29 mins       ███████░░░░░░░░░░░░░░░░░░   30.51% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12%

💻 Operating System: 
Mac                      11 hrs 27 mins      █████████████████████████   100.0%

```


 Last Updated on 29/11/2025 18:45:46 UTC
<!--END_SECTION:waka-->
