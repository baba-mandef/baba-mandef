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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C819%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   7 hrs 53 mins       ████████████░░░░░░░░░░░░░   49.6% 
Other                    4 hrs 13 mins       ██████░░░░░░░░░░░░░░░░░░░   26.57% 
HTML                     2 hrs 53 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.18% 
Image (svg)              42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.5% 
Git Config               5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.53%

🔥 Editors: 
VS Code                  11 hrs 11 mins      █████████████████░░░░░░░░   70.44% 
Terminal                 2 hrs 31 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.87% 
Notion                   56 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.92% 
Figma                    42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.5% 
GIMP                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.27%

💻 Operating System: 
Mac                      15 hrs 53 mins      █████████████████████████   100.0%

```


 Last Updated on 30/08/2025 18:42:15 UTC
<!--END_SECTION:waka-->
