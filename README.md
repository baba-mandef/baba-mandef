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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C965%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   6 hrs 23 mins       █████████░░░░░░░░░░░░░░░░   36.7% 
JavaScript               4 hrs 33 mins       ██████░░░░░░░░░░░░░░░░░░░   26.17% 
HTML                     4 hrs 32 mins       ██████░░░░░░░░░░░░░░░░░░░   26.02% 
Other                    1 hr 54 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.99% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

🔥 Editors: 
VS Code                  15 hrs 30 mins      ██████████████████████░░░   89.0% 
GIMP                     45 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.36% 
Terminal                 45 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.36% 
Notion                   23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.29%

💻 Operating System: 
Mac                      17 hrs 25 mins      █████████████████████████   100.0%

```


 Last Updated on 07/01/2026 18:54:39 UTC
<!--END_SECTION:waka-->
