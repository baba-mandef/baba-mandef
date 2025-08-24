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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C804%20hrs%2012%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   19 hrs 2 mins       █████████████░░░░░░░░░░░░   53.39% 
HTML                     12 hrs 47 mins      █████████░░░░░░░░░░░░░░░░   35.88% 
Other                    2 hrs 21 mins       █░░░░░░░░░░░░░░░░░░░░░░░░   6.62% 
CSS                      40 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.9% 
Image (svg)              36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.72%

🔥 Editors: 
VS Code                  33 hrs              ███████████████████████░░   92.56% 
Terminal                 1 hr 15 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   3.51% 
Figma                    36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.72% 
Notion                   25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.19% 
GIMP                     21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.99%

💻 Operating System: 
Mac                      35 hrs 40 mins      █████████████████████████   100.0%

```


 Last Updated on 24/08/2025 18:44:30 UTC
<!--END_SECTION:waka-->
