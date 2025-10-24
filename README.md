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
HTML                     44 mins             ██████████████░░░░░░░░░░░   56.77% 
Other                    25 mins             ████████░░░░░░░░░░░░░░░░░   32.07% 
Python                   8 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   10.53% 
XML                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.61% 
Groff                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

🔥 Editors: 
VS Code                  53 mins             █████████████████░░░░░░░░   67.91% 
Notion                   16 mins             █████░░░░░░░░░░░░░░░░░░░░   20.91% 
Terminal                 4 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.99% 
GIMP                     3 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.93% 
Notes                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26%

💻 Operating System: 
Mac                      1 hr 19 mins        █████████████████████████   100.0%

```


 Last Updated on 24/10/2025 18:44:55 UTC
<!--END_SECTION:waka-->
