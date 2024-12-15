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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C291%20hrs%2059%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 27 mins       ██████████████░░░░░░░░░░░   58.07% 
JavaScript               3 hrs 29 mins       ██████░░░░░░░░░░░░░░░░░░░   23.98% 
HTML                     2 hrs 34 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.69% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14% 
SQL                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  14 hrs 33 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 14 hrs 33 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    14 hrs 33 mins      █████████████████████████   100.0%

```


 Last Updated on 15/12/2024 18:42:27 UTC
<!--END_SECTION:waka-->
