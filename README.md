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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C309%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 54 mins       █████████████░░░░░░░░░░░░   55.48% 
HTML                     6 hrs 21 mins       ██████████░░░░░░░░░░░░░░░   39.62% 
JavaScript               36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.75% 
Text                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

🔥 Editors: 
VS Code                  16 hrs 4 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 9 hrs 30 mins       ██████████████░░░░░░░░░░░   59.22% 
investioo                6 hrs 5 mins        █████████░░░░░░░░░░░░░░░░   37.88% 
default                  28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.91%

💻 Operating System: 
Linux                    16 hrs 4 mins       █████████████████████████   100.0%

```


 Last Updated on 24/12/2024 18:41:17 UTC
<!--END_SECTION:waka-->
