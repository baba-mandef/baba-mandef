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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C527%20hrs%2012%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     8 hrs 19 mins       ████████████░░░░░░░░░░░░░   48.49% 
Python                   7 hrs 54 mins       ███████████░░░░░░░░░░░░░░   46.03% 
JavaScript               52 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.06% 
Other                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36% 
Git                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  17 hrs 10 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 10 hrs 31 mins      ███████████████░░░░░░░░░░   61.28% 
burnzzy-shop             4 hrs 48 mins       ███████░░░░░░░░░░░░░░░░░░   28.0% 
interlin                 58 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.73% 
investioo                35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.4% 
MULTI                    16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.59%

💻 Operating System: 
Linux                    17 hrs 10 mins      █████████████████████████   100.0%

```


 Last Updated on 12/02/2025 18:42:42 UTC
<!--END_SECTION:waka-->
