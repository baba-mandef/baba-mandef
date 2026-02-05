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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C982%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    41 mins             █████████░░░░░░░░░░░░░░░░   39.08% 
HTML                     24 mins             █████░░░░░░░░░░░░░░░░░░░░   23.17% 
Python                   16 mins             ███░░░░░░░░░░░░░░░░░░░░░░   15.01% 
Bash                     10 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.6% 
Image (svg)              10 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.58%

🔥 Editors: 
VS Code                  55 mins             ████████████░░░░░░░░░░░░░   51.29% 
GIMP                     28 mins             ██████░░░░░░░░░░░░░░░░░░░   26.75% 
Terminal                 12 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.02% 
Figma                    10 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.58% 
FileZilla                0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.35%

💻 Operating System: 
Mac                      1 hr 47 mins        █████████████████████████   100.0%

```


 Last Updated on 05/02/2026 19:11:19 UTC
<!--END_SECTION:waka-->
