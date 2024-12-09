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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C284%20hrs%207%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   20 hrs 9 mins       █████████████████████░░░░   85.87% 
HTML                     2 hrs 57 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.58% 
Bash                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.67% 
JavaScript               6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.49% 
CSS                      4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.29%

🔥 Editors: 
VS Code                  23 hrs 28 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 22 hrs 39 mins      ████████████████████████░   96.56% 
quatro                   48 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.44%

💻 Operating System: 
Linux                    23 hrs 28 mins      █████████████████████████   100.0%

```


 Last Updated on 09/12/2024 18:45:55 UTC
<!--END_SECTION:waka-->
