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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C927%20hrs%2058%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     9 hrs 10 mins       ███████████████░░░░░░░░░░   61.56% 
Python                   3 hrs 54 mins       ██████░░░░░░░░░░░░░░░░░░░   26.19% 
Other                    35 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.94% 
CSS                      32 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.63% 
JavaScript               28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.13%

🔥 Editors: 
VS Code                  14 hrs 15 mins      ████████████████████████░   95.64% 
GIMP                     30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.45% 
Terminal                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.48% 
Figma                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.42%

💻 Operating System: 
Mac                      14 hrs 54 mins      █████████████████████████   100.0%

```


 Last Updated on 10/12/2025 18:50:35 UTC
<!--END_SECTION:waka-->
