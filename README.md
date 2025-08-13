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
                       'languages': ['Python', 'JS', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'English', 'French'],
                       'tools': ['Django', 'React', 'Flet', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C766%20hrs%2023%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   15 hrs 22 mins      ██████████████████░░░░░░░   72.6% 
HTML                     4 hrs 30 mins       █████░░░░░░░░░░░░░░░░░░░░   21.3% 
Markdown                 28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26% 
Bash                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.34% 
Git                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84%

🔥 Editors: 
VS Code                  21 hrs 11 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      20 hrs 56 mins      ████████████████████████░   98.88% 
Linux                    14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12%

```


 Last Updated on 13/08/2025 18:49:36 UTC
<!--END_SECTION:waka-->
