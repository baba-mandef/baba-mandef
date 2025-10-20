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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C864%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 11 mins        ███████████████████████░░   92.43% 
Python                   5 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.92% 
XML                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.63% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
Notion                   55 mins             ██████████████████░░░░░░░   72.2% 
Terminal                 11 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.95% 
VS Code                  5 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   7.54% 
GIMP                     3 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.04% 
Notes                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26%

💻 Operating System: 
Mac                      1 hr 17 mins        █████████████████████████   100.0%

```


 Last Updated on 20/10/2025 18:48:56 UTC
<!--END_SECTION:waka-->
