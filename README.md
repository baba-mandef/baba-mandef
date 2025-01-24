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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C481%20hrs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   19 hrs 17 mins      █████████████░░░░░░░░░░░░   52.23% 
HTML                     15 hrs 41 mins      ██████████░░░░░░░░░░░░░░░   42.5% 
Text                     48 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.19% 
JSON                     44 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.99% 
CSS                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.48%

🔥 Editors: 
VS Code                  36 hrs 55 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 32 hrs 45 mins      ██████████████████████░░░   88.71% 
interlin                 3 hrs 35 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   9.74% 
MULTI                    20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94% 
suprek                   7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.33% 
antek                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.15%

💻 Operating System: 
Linux                    36 hrs 55 mins      █████████████████████████   100.0%

```


 Last Updated on 24/01/2025 18:41:26 UTC
<!--END_SECTION:waka-->
