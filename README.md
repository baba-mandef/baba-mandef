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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C863%20hrs%201%20min-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 1 min          ████████████████████████░   96.76% 
Python                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.24%

🔥 Editors: 
GIMP                     39 mins             ███████████████░░░░░░░░░░   62.0% 
Notion                   21 mins             ████████░░░░░░░░░░░░░░░░░   33.92% 
VS Code                  2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.24% 
Terminal                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84%

💻 Operating System: 
Mac                      1 hr 3 mins         █████████████████████████   100.0%

```


 Last Updated on 15/10/2025 18:47:31 UTC
<!--END_SECTION:waka-->
