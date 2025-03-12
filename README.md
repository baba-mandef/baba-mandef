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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C594%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 21 mins       ████████████░░░░░░░░░░░░░   48.14% 
HTML                     4 hrs 5 mins        ███████████░░░░░░░░░░░░░░   45.2% 
JavaScript               26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.84% 
CSS                      6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.25% 
Bash                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.4%

🔥 Editors: 
VS Code                  9 hrs 2 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
interlin                 5 hrs 41 mins       ███████████████░░░░░░░░░░   63.06% 
investioo                2 hrs 48 mins       ███████░░░░░░░░░░░░░░░░░░   31.0% 
abiodoun.dev             23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.41% 
wuloevents-api           8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.53%

💻 Operating System: 
Linux                    9 hrs 2 mins        █████████████████████████   100.0%

```


 Last Updated on 12/03/2025 18:44:56 UTC
<!--END_SECTION:waka-->
