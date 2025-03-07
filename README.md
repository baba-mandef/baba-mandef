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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C585%20hrs%2038%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     11 hrs 12 mins      █████████████░░░░░░░░░░░░   53.36% 
Python                   8 hrs 15 mins       █████████░░░░░░░░░░░░░░░░   39.33% 
JavaScript               1 hr 3 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.05% 
Text                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.13% 
JSON                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.87%

🔥 Editors: 
VS Code                  21 hrs              █████████████████████████   100.0%

🐱‍💻 Projects: 
dreambigforinculsion     10 hrs 27 mins      ████████████░░░░░░░░░░░░░   49.78% 
investioo-finance        8 hrs 8 mins        █████████░░░░░░░░░░░░░░░░   38.76% 
investioo                2 hrs 4 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.91% 
jago-welfare             10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81% 
dist                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.43%

💻 Operating System: 
Linux                    21 hrs              █████████████████████████   100.0%

```


 Last Updated on 07/03/2025 18:42:56 UTC
<!--END_SECTION:waka-->
