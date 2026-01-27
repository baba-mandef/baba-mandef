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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C974%20hrs%2050%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   45 mins             ██████████░░░░░░░░░░░░░░░   42.63% 
Other                    40 mins             █████████░░░░░░░░░░░░░░░░   38.07% 
Image (svg)              20 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.87% 
PHP                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

🔥 Editors: 
VS Code                  52 mins             ████████████░░░░░░░░░░░░░   49.23% 
Terminal                 34 mins             ████████░░░░░░░░░░░░░░░░░   31.9% 
Figma                    20 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.87%

💻 Operating System: 
Mac                      1 hr 47 mins        █████████████████████████   100.0%

```


 Last Updated on 27/01/2026 19:02:17 UTC
<!--END_SECTION:waka-->
