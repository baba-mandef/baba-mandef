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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C300%20hrs%201%20min-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   7 hrs 37 mins       █████████████░░░░░░░░░░░░   54.78% 
JavaScript               4 hrs 22 mins       ███████░░░░░░░░░░░░░░░░░░   31.48% 
HTML                     1 hr 45 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.6% 
Dart                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.67% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.47%

🔥 Editors: 
VS Code                  13 hrs 54 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 13 hrs 48 mins      ████████████████████████░   99.33% 
ishiro                   5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.67%

💻 Operating System: 
Linux                    13 hrs 54 mins      █████████████████████████   100.0%

```


 Last Updated on 20/12/2024 18:41:40 UTC
<!--END_SECTION:waka-->
