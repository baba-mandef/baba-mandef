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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C378%20hrs%2049%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   17 hrs 15 mins      ██████████████░░░░░░░░░░░   55.74% 
HTML                     13 hrs 9 mins       ██████████░░░░░░░░░░░░░░░   42.5% 
JavaScript               26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.41% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

🔥 Editors: 
VS Code                  30 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                16 hrs 3 mins       █████████████░░░░░░░░░░░░   51.86% 
ekilibre                 14 hrs 44 mins      ████████████░░░░░░░░░░░░░   47.63% 
MULTI                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52%

💻 Operating System: 
Linux                    30 hrs 57 mins      █████████████████████████   100.0%

```


 Last Updated on 07/01/2025 18:42:22 UTC
<!--END_SECTION:waka-->
