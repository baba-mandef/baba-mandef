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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C860%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   1 hr 43 mins        ████████████░░░░░░░░░░░░░   48.8% 
Other                    1 hr 17 mins        █████████░░░░░░░░░░░░░░░░   36.39% 
HTML                     24 mins             ███░░░░░░░░░░░░░░░░░░░░░░   11.61% 
JavaScript               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.54% 
TOML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94%

🔥 Editors: 
VS Code                  2 hrs 24 mins       █████████████████░░░░░░░░   67.78% 
FileZilla                47 mins             █████░░░░░░░░░░░░░░░░░░░░   22.11% 
Notes                    19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.94% 
Terminal                 2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.03% 
Postman                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

💻 Operating System: 
Mac                      3 hrs 22 mins       ███████████████████████░░   95.21% 
Linux                    10 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.79%

```


 Last Updated on 04/10/2025 18:42:14 UTC
<!--END_SECTION:waka-->
