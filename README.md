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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C364%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   14 hrs 56 mins      ██████████████░░░░░░░░░░░   57.9% 
HTML                     10 hrs 41 mins      ██████████░░░░░░░░░░░░░░░   41.44% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

🔥 Editors: 
VS Code                  25 hrs 48 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                21 hrs 32 mins      ████████████████████░░░░░   83.49% 
ekilibre                 4 hrs 3 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.75% 
demo                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.55% 
hudim                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

💻 Operating System: 
Linux                    25 hrs 48 mins      █████████████████████████   100.0%

```


 Last Updated on 04/01/2025 18:40:25 UTC
<!--END_SECTION:waka-->
