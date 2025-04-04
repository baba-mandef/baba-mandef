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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C615%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1338-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 16 mins       ██████████░░░░░░░░░░░░░░░   40.0% 
HTML                     4 hrs 4 mins        █████████░░░░░░░░░░░░░░░░   38.14% 
JavaScript               1 hr 2 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   9.72% 
Text                     42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.59% 
CSS                      33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.3%

🔥 Editors: 
VS Code                  10 hrs 40 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        5 hrs 42 mins       █████████████░░░░░░░░░░░░   53.44% 
api.checkupclimat.com    3 hrs 54 mins       █████████░░░░░░░░░░░░░░░░   36.58% 
solak                    30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.71% 
rezolusoft.com           26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.2% 
dist                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.08%

💻 Operating System: 
Linux                    10 hrs 40 mins      █████████████████████████   100.0%

```


 Last Updated on 04/04/2025 18:44:18 UTC
<!--END_SECTION:waka-->
