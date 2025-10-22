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
Other                    1 hr 25 mins        █████████████████░░░░░░░░   70.32% 
HTML                     32 mins             ██████░░░░░░░░░░░░░░░░░░░   26.55% 
Python                   3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.72% 
XML                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.4% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
Notion                   1 hr 10 mins        ██████████████░░░░░░░░░░░   57.52% 
VS Code                  36 mins             ███████░░░░░░░░░░░░░░░░░░   29.66% 
Terminal                 11 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.46% 
GIMP                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.19% 
Notes                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

💻 Operating System: 
Mac                      2 hrs 2 mins        █████████████████████████   100.0%

```


 Last Updated on 22/10/2025 18:49:14 UTC
<!--END_SECTION:waka-->
