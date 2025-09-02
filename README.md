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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C824%20hrs%206%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   1 hr 43 mins        ███████████░░░░░░░░░░░░░░   46.33% 
Other                    1 hr 25 mins        █████████░░░░░░░░░░░░░░░░   38.27% 
Image (svg)              25 mins             ███░░░░░░░░░░░░░░░░░░░░░░   11.58% 
HTML                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.31% 
SQL                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77%

🔥 Editors: 
VS Code                  1 hr 55 mins        █████████████░░░░░░░░░░░░   51.68% 
Notion                   1 hr 16 mins        ████████░░░░░░░░░░░░░░░░░   34.12% 
Figma                    25 mins             ███░░░░░░░░░░░░░░░░░░░░░░   11.58% 
Terminal                 5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.62%

💻 Operating System: 
Mac                      3 hrs 44 mins       █████████████████████████   100.0%

```


 Last Updated on 02/09/2025 18:43:45 UTC
<!--END_SECTION:waka-->
