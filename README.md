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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C602%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 33 mins       ████████████████░░░░░░░░░   63.75% 
HTML                     1 hr 44 mins        ███████░░░░░░░░░░░░░░░░░░   31.09% 
JavaScript               10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.21% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.92% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  5 hrs 34 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        5 hrs 16 mins       ███████████████████████░░   94.41% 
interlin                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.25% 
abiodoun.dev             6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95% 
dist                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.25% 
ekilibre                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

💻 Operating System: 
Linux                    5 hrs 34 mins       █████████████████████████   100.0%

```


 Last Updated on 23/03/2025 18:41:41 UTC
<!--END_SECTION:waka-->
