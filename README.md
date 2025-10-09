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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C862%20hrs%2051%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   1 hr 4 mins         █████████░░░░░░░░░░░░░░░░   37.47% 
Other                    1 hr 4 mins         █████████░░░░░░░░░░░░░░░░   37.27% 
HTML                     23 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.6% 
TOML                     8 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.99% 
Git Config               4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.86%

🔥 Editors: 
VS Code                  1 hr 48 mins        ███████████████░░░░░░░░░░   62.87% 
GIMP                     39 mins             █████░░░░░░░░░░░░░░░░░░░░   22.91% 
Notion                   24 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.95% 
Terminal                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.28%

💻 Operating System: 
Mac                      2 hrs 52 mins       █████████████████████████   99.81% 
Linux                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

```


 Last Updated on 09/10/2025 18:46:10 UTC
<!--END_SECTION:waka-->
