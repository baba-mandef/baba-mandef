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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C405%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   18 hrs 55 mins      ████████████░░░░░░░░░░░░░   49.05% 
HTML                     18 hrs 17 mins      ███████████░░░░░░░░░░░░░░   47.42% 
CSS                      35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.53% 
JavaScript               27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.2% 
JSON                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.48%

🔥 Editors: 
VS Code                  38 hrs 35 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 26 hrs 57 mins      █████████████████░░░░░░░░   69.85% 
investioo                11 hrs 17 mins      ███████░░░░░░░░░░░░░░░░░░   29.26% 
MULTI                    19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.83% 
default                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

💻 Operating System: 
Linux                    38 hrs 35 mins      █████████████████████████   100.0%

```


 Last Updated on 11/01/2025 18:40:09 UTC
<!--END_SECTION:waka-->
