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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C676%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 28 mins       █████████████░░░░░░░░░░░░   52.68% 
Python                   4 hrs 36 mins       ███████████░░░░░░░░░░░░░░   44.29% 
Text                     4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.71% 
JavaScript               4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.66% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57%

🔥 Editors: 
VS Code                  10 hrs 24 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    10 hrs 24 mins      █████████████████████████   100.0%

```


 Last Updated on 08/06/2025 18:45:10 UTC
<!--END_SECTION:waka-->
