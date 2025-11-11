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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C881%20hrs%2018%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 49 mins       █████████░░░░░░░░░░░░░░░░   38.9% 
Other                    2 hrs 24 mins       ████████░░░░░░░░░░░░░░░░░   33.26% 
HTML                     46 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.75% 
JavaScript               29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.84% 
JSON                     20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.61%

🔥 Editors: 
VS Code                  4 hrs 45 mins       ████████████████░░░░░░░░░   65.56% 
Notion                   1 hr 9 mins         ████░░░░░░░░░░░░░░░░░░░░░   15.86% 
Terminal                 54 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.49% 
GIMP                     21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.88% 
Figma                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.15%

💻 Operating System: 
Mac                      7 hrs 15 mins       █████████████████████████   100.0%

```


 Last Updated on 11/11/2025 18:47:54 UTC
<!--END_SECTION:waka-->
