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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C539%20hrs%2043%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     3 hrs 30 mins       ███████████████░░░░░░░░░░   60.84% 
Python                   1 hr 15 mins        █████░░░░░░░░░░░░░░░░░░░░   21.88% 
Gettext Catalog          30 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.93% 
CSS                      15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.54% 
JSON                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.9%

🔥 Editors: 
VS Code                  5 hrs 46 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                2 hrs 52 mins       ████████████░░░░░░░░░░░░░   49.71% 
2a7affc126b26b02f2edeb69d2 hrs 3 mins        █████████░░░░░░░░░░░░░░░░   35.8% 
ekilibre                 26 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.79% 
burnzzy-shop             8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.52% 
ishiro                   6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.92%

💻 Operating System: 
Linux                    5 hrs 46 mins       █████████████████████████   100.0%

```


 Last Updated on 21/02/2025 18:41:56 UTC
<!--END_SECTION:waka-->
