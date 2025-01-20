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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C469%20hrs%2057%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     25 hrs 23 mins      █████████████░░░░░░░░░░░░   52.57% 
Python                   21 hrs 3 mins       ███████████░░░░░░░░░░░░░░   43.59% 
Gettext Catalog          1 hr 2 mins         ░░░░░░░░░░░░░░░░░░░░░░░░░   2.14% 
JavaScript               19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.68% 
JSON                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.37%

🔥 Editors: 
VS Code                  48 hrs 18 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 42 hrs 21 mins      ██████████████████████░░░   87.69% 
investioo                5 hrs 9 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.67% 
MULTI                    36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.27% 
interlin                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.37%

💻 Operating System: 
Linux                    48 hrs 18 mins      █████████████████████████   100.0%

```


 Last Updated on 20/01/2025 18:40:14 UTC
<!--END_SECTION:waka-->
