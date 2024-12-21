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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C302%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 19 mins       ████████████████░░░░░░░░░   65.62% 
JavaScript               2 hrs 40 mins       █████░░░░░░░░░░░░░░░░░░░░   21.02% 
HTML                     1 hr 31 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.07% 
Dart                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52%

🔥 Editors: 
VS Code                  12 hrs 41 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 12 hrs 35 mins      ████████████████████████░   99.26% 
ishiro                   5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.74%

💻 Operating System: 
Linux                    12 hrs 41 mins      █████████████████████████   100.0%

```


 Last Updated on 21/12/2024 18:39:25 UTC
<!--END_SECTION:waka-->
