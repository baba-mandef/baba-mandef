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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C681%20hrs%2015%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 56 mins       ██████████████░░░░░░░░░░░   57.47% 
Markdown                 48 mins             ████░░░░░░░░░░░░░░░░░░░░░   15.66% 
TOML                     32 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.72% 
HTML                     24 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.06% 
CSS                      22 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.28%

🔥 Editors: 
VS Code                  5 hrs 7 mins        █████████████████████████   100.0%

💻 Operating System: 
Linux                    5 hrs 7 mins        █████████████████████████   100.0%

```


 Last Updated on 15/06/2025 18:44:44 UTC
<!--END_SECTION:waka-->
