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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C868%20hrs%2030%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 51 mins       █████████████████░░░░░░░░   67.9% 
HTML                     51 mins             █████░░░░░░░░░░░░░░░░░░░░   20.39% 
Python                   26 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.65% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.96% 
Git                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

🔥 Editors: 
GIMP                     1 hr 56 mins        ███████████░░░░░░░░░░░░░░   46.36% 
VS Code                  1 hr 20 mins        ████████░░░░░░░░░░░░░░░░░   32.1% 
Terminal                 37 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.98% 
Notion                   16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.56%

💻 Operating System: 
Mac                      4 hrs 12 mins       █████████████████████████   100.0%

```


 Last Updated on 26/10/2025 18:44:11 UTC
<!--END_SECTION:waka-->
