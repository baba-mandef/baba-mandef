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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C431%20hrs%2020%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     25 hrs 9 mins       █████████████░░░░░░░░░░░░   54.06% 
Python                   18 hrs 55 mins      ██████████░░░░░░░░░░░░░░░   40.64% 
Gettext Catalog          1 hr 12 mins        ░░░░░░░░░░░░░░░░░░░░░░░░░   2.6% 
CSS                      35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.27% 
Text                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

🔥 Editors: 
VS Code                  46 hrs 33 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                25 hrs 41 mins      █████████████░░░░░░░░░░░░   55.2% 
ekilibre                 20 hrs 33 mins      ███████████░░░░░░░░░░░░░░   44.17% 
MULTI                    16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.58% 
default                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

💻 Operating System: 
Linux                    46 hrs 33 mins      █████████████████████████   100.0%

```


 Last Updated on 14/01/2025 18:41:19 UTC
<!--END_SECTION:waka-->
