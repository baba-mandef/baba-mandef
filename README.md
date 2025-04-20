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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C641%20hrs%2037%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 56 mins       ██████████████░░░░░░░░░░░   57.45% 
JavaScript               2 hrs 54 mins       ███████░░░░░░░░░░░░░░░░░░   28.1% 
Python                   1 hr 19 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.77% 
CSS                      8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.42% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

🔥 Editors: 
VS Code                  10 hrs 21 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        9 hrs 58 mins       ████████████████████████░   96.38% 
interlin                 12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.07% 
crypo.netlify.app        7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.29% 
trade                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26%

💻 Operating System: 
Linux                    10 hrs 21 mins      █████████████████████████   100.0%

```


 Last Updated on 20/04/2025 18:43:23 UTC
<!--END_SECTION:waka-->
