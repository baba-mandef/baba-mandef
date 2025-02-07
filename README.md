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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C517%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     7 hrs 44 mins       ███████████░░░░░░░░░░░░░░   46.22% 
Python                   7 hrs 35 mins       ███████████░░░░░░░░░░░░░░   45.33% 
Bash                     37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.71% 
Text                     21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.16% 
JavaScript               19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.9%

🔥 Editors: 
VS Code                  16 hrs 45 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
burnzzy-shop             9 hrs 47 mins       ██████████████░░░░░░░░░░░   58.46% 
ges-emp                  4 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   26.4% 
interlin                 1 hr 32 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.18% 
ekilibre                 36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.68% 
abiodoun.dev             9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.99%

💻 Operating System: 
Linux                    16 hrs 45 mins      █████████████████████████   100.0%

```


 Last Updated on 07/02/2025 18:41:46 UTC
<!--END_SECTION:waka-->
