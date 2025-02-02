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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C501%20hrs%2036%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 43 mins       ██████████████░░░░░░░░░░░   57.86% 
HTML                     6 hrs 13 mins       █████████░░░░░░░░░░░░░░░░   37.04% 
Text                     36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.57% 
Git Config               9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89% 
Bash                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57%

🔥 Editors: 
VS Code                  16 hrs 48 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 9 hrs 32 mins       ██████████████░░░░░░░░░░░   56.73% 
ekilibre                 5 hrs 31 mins       ████████░░░░░░░░░░░░░░░░░   32.88% 
investioo                1 hr 14 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.42% 
agri-pelle               26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.64% 
suprek                   3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.33%

💻 Operating System: 
Linux                    16 hrs 48 mins      █████████████████████████   100.0%

```


 Last Updated on 02/02/2025 18:40:12 UTC
<!--END_SECTION:waka-->
