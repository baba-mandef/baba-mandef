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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C306%20hrs%2043%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 18 mins       ████████████████░░░░░░░░░   65.53% 
HTML                     2 hrs 51 mins       █████░░░░░░░░░░░░░░░░░░░░   20.16% 
JavaScript               1 hr 42 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.09% 
Text                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.06% 
Dart                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.66%

🔥 Editors: 
VS Code                  14 hrs 11 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 11 hrs 31 mins      ████████████████████░░░░░   81.17% 
investioo                2 hrs 28 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.45% 
default                  6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.72% 
ishiro                   5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.66%

💻 Operating System: 
Linux                    14 hrs 11 mins      █████████████████████████   100.0%

```


 Last Updated on 23/12/2024 18:41:19 UTC
<!--END_SECTION:waka-->
