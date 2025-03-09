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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C594%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     10 hrs 8 mins       █████████████░░░░░░░░░░░░   53.01% 
Python                   8 hrs 37 mins       ███████████░░░░░░░░░░░░░░   45.1% 
Text                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.67% 
JavaScript               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

🔥 Editors: 
VS Code                  19 hrs 7 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
dreambigforinculsion     10 hrs 27 mins      █████████████░░░░░░░░░░░░   54.69% 
interlin                 5 hrs 41 mins       ███████░░░░░░░░░░░░░░░░░░   29.78% 
investioo                2 hrs 47 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.64% 
jago-welfare             10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.89%

💻 Operating System: 
Linux                    19 hrs 7 mins       █████████████████████████   100.0%

```


 Last Updated on 09/03/2025 18:34:40 UTC
<!--END_SECTION:waka-->
