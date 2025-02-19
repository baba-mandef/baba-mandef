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
HTML                     6 hrs 12 mins       ██████████████░░░░░░░░░░░   56.91% 
Python                   3 hrs 32 mins       ████████░░░░░░░░░░░░░░░░░   32.53% 
Gettext Catalog          30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.73% 
CSS                      19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.99% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.16%

🔥 Editors: 
VS Code                  10 hrs 53 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
2a7affc126b26b02f2edeb69d3 hrs 33 mins       ████████░░░░░░░░░░░░░░░░░   32.6% 
investioo                2 hrs 53 mins       ██████░░░░░░░░░░░░░░░░░░░   26.58% 
interlin                 2 hrs 33 mins       █████░░░░░░░░░░░░░░░░░░░░   23.48% 
ekilibre                 1 hr 24 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.86% 
burnzzy-shop             8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.33%

💻 Operating System: 
Linux                    10 hrs 53 mins      █████████████████████████   100.0%

```


 Last Updated on 19/02/2025 18:42:46 UTC
<!--END_SECTION:waka-->
