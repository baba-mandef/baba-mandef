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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C496%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   10 hrs 9 mins       ████████████░░░░░░░░░░░░░   49.09% 
HTML                     8 hrs 7 mins        █████████░░░░░░░░░░░░░░░░   39.22% 
JSON                     1 hr 5 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.25% 
Text                     38 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.13% 
CSS                      21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.75%

🔥 Editors: 
VS Code                  20 hrs 42 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 11 hrs 9 mins       █████████████░░░░░░░░░░░░   53.87% 
interlin                 6 hrs 30 mins       ███████░░░░░░░░░░░░░░░░░░   31.41% 
investioo                2 hrs 19 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   11.23% 
agri-pelle               26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.14% 
suprek                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84%

💻 Operating System: 
Linux                    20 hrs 42 mins      █████████████████████████   100.0%

```


 Last Updated on 29/01/2025 18:41:32 UTC
<!--END_SECTION:waka-->
