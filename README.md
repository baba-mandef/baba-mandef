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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C860%20hrs%202%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 23 mins        ███████████░░░░░░░░░░░░░░   44.74% 
Python                   1 hr 13 mins        █████████░░░░░░░░░░░░░░░░   39.17% 
HTML                     23 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.59% 
JavaScript               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.76% 
TOML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.07%

🔥 Editors: 
VS Code                  1 hr 42 mins        █████████████░░░░░░░░░░░░   55.03% 
FileZilla                47 mins             ██████░░░░░░░░░░░░░░░░░░░   25.26% 
Notes                    19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.21% 
Terminal                 17 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.27% 
Figma                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.22%

💻 Operating System: 
Mac                      3 hrs 6 mins        █████████████████████████   100.0%

```


 Last Updated on 01/10/2025 18:46:07 UTC
<!--END_SECTION:waka-->
