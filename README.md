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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C656%20hrs%2058%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 52 mins       ███████████████░░░░░░░░░░   63.19% 
JavaScript               2 hrs 32 mins       █████░░░░░░░░░░░░░░░░░░░░   23.36% 
Python                   1 hr 14 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   11.37% 
CSS                      8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.28% 
YAML                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.56%

🔥 Editors: 
VS Code                  10 hrs 52 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    10 hrs 52 mins      █████████████████████████   100.0%

```


 Last Updated on 10/05/2025 18:42:13 UTC
<!--END_SECTION:waka-->
