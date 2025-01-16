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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C440%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     27 hrs 17 mins      █████████████░░░░░░░░░░░░   53.17% 
Python                   21 hrs 28 mins      ██████████░░░░░░░░░░░░░░░   41.83% 
Gettext Catalog          1 hr 12 mins        ░░░░░░░░░░░░░░░░░░░░░░░░░   2.36% 
CSS                      31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.02% 
JavaScript               19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.63%

🔥 Editors: 
VS Code                  51 hrs 19 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 28 hrs 41 mins      ██████████████░░░░░░░░░░░   55.88% 
investioo                22 hrs 26 mins      ███████████░░░░░░░░░░░░░░   43.73% 
MULTI                    11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.38%

💻 Operating System: 
Linux                    51 hrs 19 mins      █████████████████████████   100.0%

```


 Last Updated on 16/01/2025 18:41:01 UTC
<!--END_SECTION:waka-->
