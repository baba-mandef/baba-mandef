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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C294%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   6 hrs 26 mins       █████████████░░░░░░░░░░░░   51.69% 
JavaScript               3 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   27.44% 
HTML                     2 hrs 33 mins       █████░░░░░░░░░░░░░░░░░░░░   20.57% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17% 
SQL                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

🔥 Editors: 
VS Code                  12 hrs 28 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 12 hrs 28 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    12 hrs 28 mins      █████████████████████████   100.0%

```


 Last Updated on 16/12/2024 18:45:39 UTC
<!--END_SECTION:waka-->
