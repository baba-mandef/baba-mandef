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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C535%20hrs%2028%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 14 mins       ██████████████░░░░░░░░░░░   55.84% 
Python                   3 hrs 50 mins       ████████░░░░░░░░░░░░░░░░░   34.27% 
Gettext Catalog          30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.6% 
CSS                      16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.53% 
JSON                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.13%

🔥 Editors: 
VS Code                  11 hrs 11 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                2 hrs 53 mins       ██████░░░░░░░░░░░░░░░░░░░   25.88% 
2a7affc126b26b02f2edeb69d2 hrs 43 mins       ██████░░░░░░░░░░░░░░░░░░░   24.28% 
interlin                 2 hrs 34 mins       █████░░░░░░░░░░░░░░░░░░░░   22.98% 
ekilibre                 2 hrs 31 mins       █████░░░░░░░░░░░░░░░░░░░░   22.51% 
burnzzy-shop             8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.3%

💻 Operating System: 
Linux                    11 hrs 11 mins      █████████████████████████   100.0%

```


 Last Updated on 18/02/2025 18:43:22 UTC
<!--END_SECTION:waka-->
