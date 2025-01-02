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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C356%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     17 hrs 48 mins      █████████████░░░░░░░░░░░░   54.56% 
Python                   14 hrs 39 mins      ███████████░░░░░░░░░░░░░░   44.89% 
Git Config               5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07%

🔥 Editors: 
VS Code                  32 hrs 37 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                31 hrs 41 mins      ████████████████████████░   97.14% 
ekilibre                 25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.31% 
demo                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.16% 
default                  4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.24% 
hudim                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

💻 Operating System: 
Linux                    32 hrs 37 mins      █████████████████████████   100.0%

```


 Last Updated on 02/01/2025 18:41:50 UTC
<!--END_SECTION:waka-->
