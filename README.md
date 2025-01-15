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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C434%20hrs%2034%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     28 hrs 36 mins      █████████████░░░░░░░░░░░░   53.45% 
Python                   22 hrs 17 mins      ██████████░░░░░░░░░░░░░░░   41.64% 
Gettext Catalog          1 hr 12 mins        ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26% 
CSS                      35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.1% 
JavaScript               19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.6%

🔥 Editors: 
VS Code                  53 hrs 31 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 27 hrs 44 mins      █████████████░░░░░░░░░░░░   51.83% 
investioo                25 hrs 29 mins      ████████████░░░░░░░░░░░░░   47.62% 
MULTI                    16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.51% 
default                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

💻 Operating System: 
Linux                    53 hrs 31 mins      █████████████████████████   100.0%

```


 Last Updated on 15/01/2025 18:40:45 UTC
<!--END_SECTION:waka-->
