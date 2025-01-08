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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C385%20hrs%2047%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   15 hrs 27 mins      ███████████████░░░░░░░░░░   59.63% 
HTML                     9 hrs 50 mins       █████████░░░░░░░░░░░░░░░░   37.95% 
JavaScript               26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.68% 
Other                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.42% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21%

🔥 Editors: 
VS Code                  25 hrs 55 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 17 hrs 6 mins       ████████████████░░░░░░░░░   66.0% 
investioo                8 hrs 35 mins       ████████░░░░░░░░░░░░░░░░░   33.16% 
MULTI                    13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84%

💻 Operating System: 
Linux                    25 hrs 55 mins      █████████████████████████   100.0%

```


 Last Updated on 08/01/2025 18:42:39 UTC
<!--END_SECTION:waka-->
