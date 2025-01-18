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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C452%20hrs%2037%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     27 hrs 37 mins      ██████████████░░░░░░░░░░░   56.02% 
Python                   19 hrs 42 mins      ██████████░░░░░░░░░░░░░░░   39.94% 
Gettext Catalog          1 hr 12 mins        ░░░░░░░░░░░░░░░░░░░░░░░░░   2.45% 
JavaScript               19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.65% 
Text                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.64%

🔥 Editors: 
VS Code                  49 hrs 19 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 31 hrs 57 mins      ████████████████░░░░░░░░░   64.78% 
investioo                16 hrs 50 mins      ████████░░░░░░░░░░░░░░░░░   34.15% 
MULTI                    31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.07%

💻 Operating System: 
Linux                    49 hrs 19 mins      █████████████████████████   100.0%

```


 Last Updated on 18/01/2025 18:38:40 UTC
<!--END_SECTION:waka-->
