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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C657%20hrs%2036%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     7 hrs 37 mins       ████████████████░░░░░░░░░   65.3% 
JavaScript               2 hrs 32 mins       █████░░░░░░░░░░░░░░░░░░░░   21.77% 
Python                   1 hr 14 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.59% 
CSS                      11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.58% 
YAML                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52%

🔥 Editors: 
VS Code                  11 hrs 40 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    11 hrs 40 mins      █████████████████████████   100.0%

```


 Last Updated on 11/05/2025 18:43:09 UTC
<!--END_SECTION:waka-->
