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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C286%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   13 hrs 37 mins      ███████████████████░░░░░░   77.48% 
HTML                     3 hrs 4 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.52% 
JavaScript               47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.47% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.32% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12%

🔥 Editors: 
VS Code                  17 hrs 34 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 16 hrs 46 mins      ███████████████████████░░   95.4% 
quatro                   48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.6%

💻 Operating System: 
Linux                    17 hrs 34 mins      █████████████████████████   100.0%

```


 Last Updated on 13/12/2024 18:44:41 UTC
<!--END_SECTION:waka-->
