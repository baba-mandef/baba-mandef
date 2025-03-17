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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C596%20hrs%2039%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 3 mins        █████████████████████░░░░   83.81% 
JavaScript               23 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.19%

🔥 Editors: 
VS Code                  2 hrs 27 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
wuloevents-api           2 hrs               ████████████████████░░░░░   81.73% 
abiodoun.dev             23 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.19% 
dreambigforinculsion     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.08%

💻 Operating System: 
Linux                    2 hrs 27 mins       █████████████████████████   100.0%

```


 Last Updated on 17/03/2025 18:43:13 UTC
<!--END_SECTION:waka-->
