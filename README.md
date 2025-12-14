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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C928%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     2 hrs 24 mins       ██████████████████████░░░   89.05% 
Other                    9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.04% 
Image (svg)              4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.97% 
Python                   3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.93%

🔥 Editors: 
VS Code                  2 hrs 27 mins       ██████████████████████░░░   90.98% 
Terminal                 9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.04% 
Figma                    4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.97%

💻 Operating System: 
Mac                      2 hrs 42 mins       █████████████████████████   100.0%

```


 Last Updated on 14/12/2025 18:47:13 UTC
<!--END_SECTION:waka-->
