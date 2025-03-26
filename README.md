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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C607%20hrs%2015%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 2 mins        ██████████░░░░░░░░░░░░░░░   41.13% 
HTML                     3 hrs 30 mins       █████████░░░░░░░░░░░░░░░░   35.65% 
CSS                      1 hr 55 mins        █████░░░░░░░░░░░░░░░░░░░░   19.61% 
JavaScript               11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.9% 
Text                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.61%

🔥 Editors: 
VS Code                  9 hrs 49 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        5 hrs 8 mins        █████████████░░░░░░░░░░░░   52.3% 
rezolusoft.com           4 hrs 22 mins       ███████████░░░░░░░░░░░░░░   44.61% 
interlin                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.85% 
abiodoun.dev             6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.11% 
dist                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

💻 Operating System: 
Linux                    9 hrs 49 mins       █████████████████████████   100.0%

```


 Last Updated on 26/03/2025 18:45:09 UTC
<!--END_SECTION:waka-->
