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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C861%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 18 mins       ████████████░░░░░░░░░░░░░   51.33% 
Other                    1 hr 5 mins         ██████░░░░░░░░░░░░░░░░░░░   24.18% 
HTML                     45 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.67% 
TOML                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.2% 
Git Config               5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.93%

🔥 Editors: 
VS Code                  3 hrs 34 mins       ███████████████████░░░░░░   79.1% 
FileZilla                47 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.39% 
Notion                   9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.4% 
Postman                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

💻 Operating System: 
Mac                      4 hrs 20 mins       ████████████████████████░   96.11% 
Linux                    10 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.89%

```


 Last Updated on 07/10/2025 18:46:53 UTC
<!--END_SECTION:waka-->
