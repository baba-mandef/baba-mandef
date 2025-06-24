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
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C692%20hrs%2051%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 46 mins       ███████████░░░░░░░░░░░░░░   45.85% 
HTML                     4 hrs 23 mins       ██████████░░░░░░░░░░░░░░░   42.16% 
CSS                      33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.31% 
Other                    16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.66% 
Text                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.62%

🔥 Editors: 
VS Code                  10 hrs 25 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    10 hrs 25 mins      █████████████████████████   100.0%

```


 Last Updated on 24/06/2025 18:48:55 UTC
<!--END_SECTION:waka-->
