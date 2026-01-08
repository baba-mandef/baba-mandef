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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C966%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    4 hrs 53 mins       ███████░░░░░░░░░░░░░░░░░░   30.47% 
JavaScript               3 hrs 49 mins       ██████░░░░░░░░░░░░░░░░░░░   23.79% 
Python                   3 hrs 45 mins       █████░░░░░░░░░░░░░░░░░░░░   23.37% 
HTML                     3 hrs 34 mins       █████░░░░░░░░░░░░░░░░░░░░   22.24% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  11 hrs 10 mins      █████████████████░░░░░░░░   69.52% 
GIMP                     3 hrs 44 mins       █████░░░░░░░░░░░░░░░░░░░░   23.27% 
Terminal                 45 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.73% 
Notion                   23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.48%

💻 Operating System: 
Mac                      16 hrs 4 mins       █████████████████████████   100.0%

```


 Last Updated on 08/01/2026 18:51:33 UTC
<!--END_SECTION:waka-->
