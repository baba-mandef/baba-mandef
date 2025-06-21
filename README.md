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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C690%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 58 mins       ███████████████░░░░░░░░░░   63.21% 
HTML                     3 hrs 16 mins       ████████░░░░░░░░░░░░░░░░░   34.59% 
Nginx                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.29% 
CSS                      4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.14%

🔥 Editors: 
VS Code                  9 hrs 27 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    9 hrs 27 mins       █████████████████████████   100.0%

```


 Last Updated on 21/06/2025 18:44:17 UTC
<!--END_SECTION:waka-->
