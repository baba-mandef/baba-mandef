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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C486%20hrs%2047%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   13 hrs 45 mins      ██████████████░░░░░░░░░░░   58.68% 
HTML                     7 hrs 12 mins       ███████░░░░░░░░░░░░░░░░░░   30.77% 
JSON                     1 hr 5 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   4.64% 
Text                     46 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.32% 
CSS                      21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55%

🔥 Editors: 
VS Code                  23 hrs 26 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 15 hrs 21 mins      ████████████████░░░░░░░░░   65.54% 
interlin                 6 hrs 15 mins       ██████░░░░░░░░░░░░░░░░░░░   26.71% 
investioo                1 hr 24 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.01% 
suprek                   14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.06% 
antek                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.69%

💻 Operating System: 
Linux                    23 hrs 26 mins      █████████████████████████   100.0%

```


 Last Updated on 27/01/2025 18:41:49 UTC
<!--END_SECTION:waka-->
