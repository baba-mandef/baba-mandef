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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C746%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   1 hr 46 mins        █████████████████████░░░░   87.49% 
TOML                     13 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.29% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.19% 
HTML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🔥 Editors: 
VS Code                  2 hrs 1 min         █████████████████████████   100.0%

💻 Operating System: 
Mac                      1 hr 55 mins        ███████████████████████░░   95.1% 
Linux                    5 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.9%

```


 Last Updated on 05/08/2025 18:55:56 UTC
<!--END_SECTION:waka-->
