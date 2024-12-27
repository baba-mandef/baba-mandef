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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C321%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   15 hrs 11 mins      █████████████░░░░░░░░░░░░   51.68% 
HTML                     13 hrs 48 mins      ███████████░░░░░░░░░░░░░░   46.97% 
Text                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.91% 
JavaScript               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.15%

🔥 Editors: 
VS Code                  29 hrs 23 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                25 hrs 2 mins       █████████████████████░░░░   85.22% 
ekilibre                 3 hrs 37 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.32% 
default                  35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.02% 
demo                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44%

💻 Operating System: 
Linux                    29 hrs 23 mins      █████████████████████████   100.0%

```


 Last Updated on 27/12/2024 18:41:06 UTC
<!--END_SECTION:waka-->
