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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C865%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 27 mins        █████████████████░░░░░░░░   70.81% 
HTML                     32 mins             ██████░░░░░░░░░░░░░░░░░░░   26.12% 
Python                   3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.67% 
XML                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.39% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
Notion                   1 hr 12 mins        ██████████████░░░░░░░░░░░   58.22% 
VS Code                  36 mins             ███████░░░░░░░░░░░░░░░░░░   29.18% 
Terminal                 11 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.3% 
GIMP                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.14% 
Notes                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

💻 Operating System: 
Mac                      2 hrs 4 mins        █████████████████████████   100.0%

```


 Last Updated on 21/10/2025 18:47:45 UTC
<!--END_SECTION:waka-->
