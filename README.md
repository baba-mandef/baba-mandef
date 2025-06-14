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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C681%20hrs%2023%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 31 mins       █████████████░░░░░░░░░░░░   52.97% 
HTML                     1 hr 21 mins        █████░░░░░░░░░░░░░░░░░░░░   20.47% 
Markdown                 48 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.06% 
TOML                     32 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.26% 
CSS                      22 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.61%

🔥 Editors: 
VS Code                  6 hrs 38 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    6 hrs 38 mins       █████████████████████████   100.0%

```


 Last Updated on 14/06/2025 18:45:20 UTC
<!--END_SECTION:waka-->
