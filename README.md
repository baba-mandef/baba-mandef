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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C517%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 34 mins       ████████████░░░░░░░░░░░░░   47.5% 
HTML                     8 hrs 20 mins       ███████████░░░░░░░░░░░░░░   46.24% 
Bash                     30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.78% 
Text                     21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.0% 
JavaScript               9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84%

🔥 Editors: 
VS Code                  18 hrs 2 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
burnzzy-shop             8 hrs 28 mins       ███████████░░░░░░░░░░░░░░   46.91% 
ges-emp                  4 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   24.51% 
ekilibre                 2 hrs 55 mins       ████░░░░░░░░░░░░░░░░░░░░░   16.2% 
interlin                 1 hr 26 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.95% 
investioo                36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.34%

💻 Operating System: 
Linux                    18 hrs 2 mins       █████████████████████████   100.0%

```


 Last Updated on 10/02/2025 18:41:30 UTC
<!--END_SECTION:waka-->
