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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C789%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   16 hrs 26 mins      ██████████████░░░░░░░░░░░   57.38% 
HTML                     9 hrs 47 mins       ████████░░░░░░░░░░░░░░░░░   34.16% 
CSS                      1 hr 10 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.07% 
Other                    43 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.54% 
TOML                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.93%

🔥 Editors: 
VS Code                  27 hrs 50 mins      ████████████████████████░   97.15% 
Notion                   25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.48% 
Terminal                 13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77% 
Figma                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.58% 
FileZilla                0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Mac                      28 hrs 35 mins      █████████████████████████   99.81% 
Linux                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.19%

```


 Last Updated on 22/08/2025 18:46:48 UTC
<!--END_SECTION:waka-->
