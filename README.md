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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C644%20hrs%2041%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   1 hr 1 min          █████████████████░░░░░░░░   69.85% 
HTML                     20 mins             █████░░░░░░░░░░░░░░░░░░░░   23.32% 
JavaScript               5 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.85% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.98%

🔥 Editors: 
VS Code                  1 hr 27 mins        █████████████████████████   100.0%

💻 Operating System: 
Linux                    1 hr 27 mins        █████████████████████████   100.0%

```


 Last Updated on 28/04/2025 18:45:54 UTC
<!--END_SECTION:waka-->
