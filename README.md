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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C913%20hrs%204%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 22 mins       ██████████░░░░░░░░░░░░░░░   41.86% 
Python                   3 hrs 58 mins       ██████░░░░░░░░░░░░░░░░░░░   26.03% 
Other                    3 hrs 31 mins       █████░░░░░░░░░░░░░░░░░░░░   23.12% 
CSS                      1 hr                █░░░░░░░░░░░░░░░░░░░░░░░░   6.64% 
JavaScript               14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.64%

🔥 Editors: 
VS Code                  11 hrs 42 mins      ███████████████████░░░░░░   76.88% 
Terminal                 2 hrs 8 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.09% 
GIMP                     1 hr 22 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.03%

💻 Operating System: 
Mac                      15 hrs 14 mins      █████████████████████████   100.0%

```


 Last Updated on 04/12/2025 18:53:06 UTC
<!--END_SECTION:waka-->
