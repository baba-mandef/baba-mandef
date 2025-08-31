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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C820%20hrs%2024%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 11 mins       ████████████░░░░░░░░░░░░░   50.12% 
Other                    2 hrs 57 mins       ███████░░░░░░░░░░░░░░░░░░   28.49% 
HTML                     1 hr 50 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.7% 
Image (svg)              16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.6% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.51%

🔥 Editors: 
VS Code                  7 hrs 8 mins        █████████████████░░░░░░░░   68.91% 
Terminal                 1 hr 30 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.56% 
Notion                   1 hr 16 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.29% 
Figma                    16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.6% 
GIMP                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.65%

💻 Operating System: 
Mac                      10 hrs 22 mins      █████████████████████████   100.0%

```


 Last Updated on 31/08/2025 18:43:46 UTC
<!--END_SECTION:waka-->
