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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C710%20hrs%2041%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     3 hrs 42 mins       ████████████░░░░░░░░░░░░░   48.63% 
Python                   2 hrs 53 mins       █████████░░░░░░░░░░░░░░░░   37.96% 
CSS                      39 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.62% 
Bash                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.39%

🔥 Editors: 
VS Code                  7 hrs 36 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    7 hrs 36 mins       █████████████████████████   100.0%

```


 Last Updated on 08/07/2025 18:49:45 UTC
<!--END_SECTION:waka-->
