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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C645%20hrs%2030%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     1 hr 2 mins         ████████████░░░░░░░░░░░░░   49.49% 
Python                   1 hr 1 min          ████████████░░░░░░░░░░░░░   48.69% 
JavaScript               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.13% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.68%

🔥 Editors: 
VS Code                  2 hrs 5 mins        █████████████████████████   100.0%

💻 Operating System: 
Linux                    2 hrs 5 mins        █████████████████████████   100.0%

```


 Last Updated on 29/04/2025 18:44:51 UTC
<!--END_SECTION:waka-->
