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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C499%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   10 hrs 23 mins      █████████████░░░░░░░░░░░░   55.46% 
HTML                     7 hrs 5 mins        █████████░░░░░░░░░░░░░░░░   37.83% 
Text                     36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.2% 
JSON                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.97% 
Git Config               9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.8%

🔥 Editors: 
VS Code                  18 hrs 45 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 9 hrs 34 mins       ████████████░░░░░░░░░░░░░   51.08% 
ekilibre                 6 hrs 23 mins       ████████░░░░░░░░░░░░░░░░░   34.1% 
investioo                2 hrs 16 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.15% 
agri-pelle               26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.36% 
suprek                   3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3%

💻 Operating System: 
Linux                    18 hrs 45 mins      █████████████████████████   100.0%

```


 Last Updated on 01/02/2025 18:38:08 UTC
<!--END_SECTION:waka-->
