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
Python                   1 hr 31 mins        ███████████████░░░░░░░░░░   59.74% 
HTML                     21 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.22% 
Other                    19 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.46% 
TOML                     8 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.62% 
Git Config               4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.22%

🔥 Editors: 
VS Code                  2 hrs 23 mins       ███████████████████████░░   93.47% 
Notion                   9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.98% 
GIMP                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.37% 
Postman                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

💻 Operating System: 
Mac                      2 hrs 23 mins       ███████████████████████░░   93.16% 
Linux                    10 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.84%

```


 Last Updated on 08/10/2025 18:47:42 UTC
<!--END_SECTION:waka-->
