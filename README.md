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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C289%20hrs%202%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   10 hrs 54 mins      █████████████████░░░░░░░░   71.02% 
JavaScript               2 hrs 29 mins       ████░░░░░░░░░░░░░░░░░░░░░   16.22% 
HTML                     1 hr 55 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.52% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14% 
SQL                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  15 hrs 21 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 14 hrs 32 mins      ███████████████████████░░   94.74% 
quatro                   48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.26%

💻 Operating System: 
Linux                    15 hrs 21 mins      █████████████████████████   100.0%

```


 Last Updated on 14/12/2024 18:42:27 UTC
<!--END_SECTION:waka-->
