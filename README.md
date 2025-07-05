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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C708%20hrs%207%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 45 mins       ██████████████████░░░░░░░   73.74% 
HTML                     38 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.27% 
Bash                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.28% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.83% 
Other                    4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.98%

🔥 Editors: 
VS Code                  3 hrs 44 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    3 hrs 44 mins       █████████████████████████   100.0%

```


 Last Updated on 05/07/2025 18:44:32 UTC
<!--END_SECTION:waka-->
