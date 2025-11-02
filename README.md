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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C870%20hrs%2053%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   1 hr 4 mins         ███████████░░░░░░░░░░░░░░   45.01% 
Markdown                 37 mins             ██████░░░░░░░░░░░░░░░░░░░   25.85% 
HTML                     15 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.9% 
Other                    14 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.93% 
Image (svg)              9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.63%

🔥 Editors: 
VS Code                  2 hrs               ████████████████████░░░░░   83.44% 
Terminal                 14 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.93% 
Figma                    9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.63%

💻 Operating System: 
Mac                      2 hrs 24 mins       █████████████████████████   100.0%

```


 Last Updated on 02/11/2025 18:41:55 UTC
<!--END_SECTION:waka-->
