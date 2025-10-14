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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C862%20hrs%2058%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    59 mins             ███████████████████████░░   93.85% 
Python                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.21% 
HTML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   2.94%

🔥 Editors: 
GIMP                     39 mins             ███████████████░░░░░░░░░░   62.27% 
Notion                   19 mins             ███████░░░░░░░░░░░░░░░░░░   30.38% 
VS Code                  4 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.51% 
Terminal                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84%

💻 Operating System: 
Mac                      1 hr 3 mins         █████████████████████████   100.0%

```


 Last Updated on 14/10/2025 18:46:04 UTC
<!--END_SECTION:waka-->
