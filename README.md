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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C297%20hrs%202%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
JavaScript               4 hrs 41 mins       █████████░░░░░░░░░░░░░░░░   37.48% 
Python                   4 hrs 22 mins       ████████░░░░░░░░░░░░░░░░░   34.94% 
HTML                     3 hrs 16 mins       ██████░░░░░░░░░░░░░░░░░░░   26.16% 
Dart                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.75% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.53%

🔥 Editors: 
VS Code                  12 hrs 30 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 12 hrs 25 mins      ████████████████████████░   99.25% 
ishiro                   5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.75%

💻 Operating System: 
Linux                    12 hrs 30 mins      █████████████████████████   100.0%

```


 Last Updated on 18/12/2024 18:44:13 UTC
<!--END_SECTION:waka-->
