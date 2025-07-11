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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C721%20hrs%2016%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 20 mins       ███████████░░░░░░░░░░░░░░   45.24% 
Python                   6 hrs 1 min         ██████████░░░░░░░░░░░░░░░   43.04% 
CSS                      39 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.68% 
Bash                     23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.78% 
Gettext Catalog          15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.89%

🔥 Editors: 
VS Code                  14 hrs              █████████████████████████   100.0%

💻 Operating System: 
Linux                    14 hrs              █████████████████████████   100.0%

```


 Last Updated on 11/07/2025 18:49:15 UTC
<!--END_SECTION:waka-->
