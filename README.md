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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C900%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 18 mins       █████████████░░░░░░░░░░░░   51.79% 
Python                   1 hr 55 mins        ██████████░░░░░░░░░░░░░░░   43.24% 
HTML                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.19% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89% 
Image (svg)              1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.73%

🔥 Editors: 
Terminal                 2 hrs 18 mins       █████████████░░░░░░░░░░░░   51.79% 
VS Code                  2 hrs 7 mins        ███████████░░░░░░░░░░░░░░   47.48% 
Figma                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.73%

💻 Operating System: 
Mac                      4 hrs 28 mins       █████████████████████████   100.0%

```


 Last Updated on 25/11/2025 18:48:53 UTC
<!--END_SECTION:waka-->
