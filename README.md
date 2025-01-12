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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C413%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   19 hrs 58 mins      ████████████░░░░░░░░░░░░░   48.96% 
HTML                     19 hrs 23 mins      ████████████░░░░░░░░░░░░░   47.5% 
CSS                      35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.45% 
JavaScript               27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.13% 
JSON                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.45%

🔥 Editors: 
VS Code                  40 hrs 48 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 26 hrs 10 mins      ████████████████░░░░░░░░░   64.16% 
investioo                14 hrs 16 mins      ████████░░░░░░░░░░░░░░░░░   35.0% 
MULTI                    19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.79% 
default                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

💻 Operating System: 
Linux                    40 hrs 48 mins      █████████████████████████   100.0%

```


 Last Updated on 12/01/2025 18:39:54 UTC
<!--END_SECTION:waka-->
