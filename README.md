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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C491%20hrs%2022%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 7 mins        ███████████░░░░░░░░░░░░░░   46.89% 
HTML                     7 hrs 12 mins       ██████████░░░░░░░░░░░░░░░   41.64% 
JSON                     1 hr 5 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   6.27% 
CSS                      21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.09% 
Text                     17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.73%

🔥 Editors: 
VS Code                  17 hrs 19 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 9 hrs 25 mins       █████████████░░░░░░░░░░░░   54.35% 
interlin                 5 hrs 42 mins       ████████░░░░░░░░░░░░░░░░░   32.94% 
investioo                1 hr 25 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.21% 
agri-pelle               26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.56% 
suprek                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.01%

💻 Operating System: 
Linux                    17 hrs 19 mins      █████████████████████████   100.0%

```


 Last Updated on 28/01/2025 18:42:20 UTC
<!--END_SECTION:waka-->
