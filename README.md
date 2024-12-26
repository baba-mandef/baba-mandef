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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C314%20hrs%2026%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   12 hrs 59 mins      ███████████████░░░░░░░░░░   59.78% 
HTML                     8 hrs 23 mins       █████████░░░░░░░░░░░░░░░░   38.6% 
Text                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.19% 
JavaScript               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.27% 
CSS                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07%

🔥 Editors: 
VS Code                  21 hrs 44 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                14 hrs 40 mins      █████████████████░░░░░░░░   67.51% 
ekilibre                 6 hrs 32 mins       ███████░░░░░░░░░░░░░░░░░░   30.12% 
default                  30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.37%

💻 Operating System: 
Linux                    21 hrs 44 mins      █████████████████████████   100.0%

```


 Last Updated on 26/12/2024 18:41:20 UTC
<!--END_SECTION:waka-->
