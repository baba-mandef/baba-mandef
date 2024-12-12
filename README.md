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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C286%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   14 hrs 25 mins      ████████████████████░░░░░   83.03% 
HTML                     2 hrs 20 mins       ███░░░░░░░░░░░░░░░░░░░░░░   13.45% 
JavaScript               31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.98% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.33% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12%

🔥 Editors: 
VS Code                  17 hrs 21 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 16 hrs 33 mins      ███████████████████████░░   95.35% 
quatro                   48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.65%

💻 Operating System: 
Linux                    17 hrs 21 mins      █████████████████████████   100.0%

```


 Last Updated on 12/12/2024 18:45:47 UTC
<!--END_SECTION:waka-->
