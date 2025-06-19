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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C687%20hrs%2029%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 53 mins       ███████████████████░░░░░░   77.5% 
HTML                     1 hr 29 mins        █████░░░░░░░░░░░░░░░░░░░░   19.67% 
Nginx                    7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.61% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.86% 
JavaScript               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36%

🔥 Editors: 
VS Code                  7 hrs 36 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    7 hrs 36 mins       █████████████████████████   100.0%

```


 Last Updated on 19/06/2025 18:46:56 UTC
<!--END_SECTION:waka-->
