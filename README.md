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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C406%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     20 hrs 51 mins      ████████████░░░░░░░░░░░░░   50.17% 
Python                   19 hrs 23 mins      ███████████░░░░░░░░░░░░░░   46.65% 
CSS                      35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.42% 
Text                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.48% 
JSON                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44%

🔥 Editors: 
VS Code                  41 hrs 34 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                20 hrs 51 mins      ████████████░░░░░░░░░░░░░   50.17% 
ekilibre                 20 hrs 31 mins      ████████████░░░░░░░░░░░░░   49.38% 
MULTI                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.39% 
default                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

💻 Operating System: 
Linux                    41 hrs 34 mins      █████████████████████████   100.0%

```


 Last Updated on 13/01/2025 18:43:58 UTC
<!--END_SECTION:waka-->
