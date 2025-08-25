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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C811%20hrs%204%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   17 hrs 13 mins      ████████████░░░░░░░░░░░░░   49.61% 
HTML                     13 hrs 25 mins      █████████░░░░░░░░░░░░░░░░   38.64% 
Other                    2 hrs 36 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   7.5% 
CSS                      40 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95% 
Image (svg)              37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.8%

🔥 Editors: 
VS Code                  31 hrs 49 mins      ███████████████████████░░   91.62% 
Terminal                 1 hr 19 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   3.82% 
Figma                    37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.8% 
GIMP                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.5% 
Notion                   25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.22%

💻 Operating System: 
Mac                      34 hrs 43 mins      █████████████████████████   100.0%

```


 Last Updated on 25/08/2025 18:48:20 UTC
<!--END_SECTION:waka-->
