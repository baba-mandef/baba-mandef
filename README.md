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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C745%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 48 mins       ██████████████████░░░░░░░   72.97% 
HTML                     1 hr 39 mins        █████░░░░░░░░░░░░░░░░░░░░   20.83% 
Git Config               14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.01% 
TOML                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.87% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.15%

🔥 Editors: 
VS Code                  7 hrs 57 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      7 hrs 52 mins       ████████████████████████░   98.76% 
Linux                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.24%

```


 Last Updated on 02/08/2025 18:49:54 UTC
<!--END_SECTION:waka-->
