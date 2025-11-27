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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C904%20hrs%2030%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     3 hrs 5 mins        ██████████░░░░░░░░░░░░░░░   40.85% 
Other                    2 hrs 40 mins       ████████░░░░░░░░░░░░░░░░░   35.28% 
Python                   1 hr 44 mins        █████░░░░░░░░░░░░░░░░░░░░   23.06% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.53% 
Image (svg)              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

🔥 Editors: 
VS Code                  4 hrs 53 mins       ████████████████░░░░░░░░░   64.53% 
Terminal                 2 hrs 40 mins       ████████░░░░░░░░░░░░░░░░░   35.28% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

💻 Operating System: 
Mac                      7 hrs 34 mins       █████████████████████████   100.0%

```


 Last Updated on 27/11/2025 18:46:38 UTC
<!--END_SECTION:waka-->
