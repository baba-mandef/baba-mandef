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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C599%20hrs%203%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 6 mins        ████████████████████████░   97.03% 
HTML                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.97%

🔥 Editors: 
VS Code                  2 hrs 10 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
wuloevents-api           1 hr 56 mins        ██████████████████████░░░   89.1% 
investioo-finance        10 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.2% 
dreambigforinculsion     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.35% 
ekilibre                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.35%

💻 Operating System: 
Linux                    2 hrs 10 mins       █████████████████████████   100.0%

```


 Last Updated on 19/03/2025 18:45:00 UTC
<!--END_SECTION:waka-->
