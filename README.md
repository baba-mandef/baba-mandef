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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C865%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     32 mins             █████████████░░░░░░░░░░░░   52.36% 
Other                    25 mins             ██████████░░░░░░░░░░░░░░░   41.48% 
Python                   3 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.35% 
XML                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.78% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  36 mins             ██████████████░░░░░░░░░░░   58.49% 
Notion                   16 mins             ██████░░░░░░░░░░░░░░░░░░░   26.66% 
Terminal                 5 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   8.22% 
GIMP                     3 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.29% 
Notes                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.33%

💻 Operating System: 
Mac                      1 hr 1 min          █████████████████████████   100.0%

```


 Last Updated on 23/10/2025 18:47:19 UTC
<!--END_SECTION:waka-->
