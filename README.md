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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C814%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   15 hrs 23 mins      ██████████░░░░░░░░░░░░░░░   43.48% 
HTML                     14 hrs 32 mins      ██████████░░░░░░░░░░░░░░░   41.1% 
Other                    3 hrs 58 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   11.23% 
CSS                      43 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.06% 
Image (svg)              37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.76%

🔥 Editors: 
VS Code                  31 hrs 6 mins       ██████████████████████░░░   87.9% 
Terminal                 2 hrs 41 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   7.62% 
Figma                    37 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.76% 
GIMP                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.48% 
Notion                   25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.2%

💻 Operating System: 
Mac                      35 hrs 23 mins      █████████████████████████   100.0%

```


 Last Updated on 26/08/2025 18:46:24 UTC
<!--END_SECTION:waka-->
