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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C663%20hrs%2059%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Dart                     3 hrs 15 mins       ██████████████████████░░░   87.55% 
HTML                     8 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.63% 
JavaScript               7 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.51% 
YAML                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.41% 
Markdown                 3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.49%

🔥 Editors: 
VS Code                  3 hrs 43 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    3 hrs 43 mins       █████████████████████████   100.0%

```


 Last Updated on 23/05/2025 18:47:04 UTC
<!--END_SECTION:waka-->
