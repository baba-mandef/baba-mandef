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
Python                   2 hrs 47 mins       ██████████████████░░░░░░░   71.77% 
HTML                     50 mins             █████░░░░░░░░░░░░░░░░░░░░   21.56% 
TOML                     13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.88% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.62% 
CSS                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

🔥 Editors: 
VS Code                  3 hrs 53 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      3 hrs 47 mins       ████████████████████████░   97.45% 
Linux                    5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.55%

```


 Last Updated on 04/08/2025 18:54:33 UTC
<!--END_SECTION:waka-->
