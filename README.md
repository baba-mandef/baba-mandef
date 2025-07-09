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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C714%20hrs%2037%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 44 mins       ███████████░░░░░░░░░░░░░░   44.69% 
HTML                     5 hrs 23 mins       ██████████░░░░░░░░░░░░░░░   41.97% 
CSS                      39 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.11% 
Bash                     23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.04% 
Gettext Catalog          15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.06%

🔥 Editors: 
VS Code                  12 hrs 50 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    12 hrs 50 mins      █████████████████████████   100.0%

```


 Last Updated on 09/07/2025 18:50:08 UTC
<!--END_SECTION:waka-->
