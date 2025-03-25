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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C606%20hrs%2013%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 42 mins       ███████████████░░░░░░░░░░   62.63% 
HTML                     1 hr 52 mins        ████████░░░░░░░░░░░░░░░░░   31.8% 
JavaScript               10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.03% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.51% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  5 hrs 55 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        5 hrs 18 mins       ██████████████████████░░░   89.61% 
rezolusoft.com           18 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.25% 
interlin                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.07% 
abiodoun.dev             6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.84% 
dist                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23%

💻 Operating System: 
Linux                    5 hrs 55 mins       █████████████████████████   100.0%

```


 Last Updated on 25/03/2025 18:44:51 UTC
<!--END_SECTION:waka-->
