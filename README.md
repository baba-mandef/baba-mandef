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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C868%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 33 mins       █████████████████░░░░░░░░   71.29% 
HTML                     33 mins             ███░░░░░░░░░░░░░░░░░░░░░░   15.49% 
Python                   25 mins             ███░░░░░░░░░░░░░░░░░░░░░░   11.99% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12% 
Git                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
GIMP                     1 hr 56 mins        █████████████░░░░░░░░░░░░   54.31% 
VS Code                  1 hr 1 min          ███████░░░░░░░░░░░░░░░░░░   28.71% 
Terminal                 36 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.98%

💻 Operating System: 
Mac                      3 hrs 35 mins       █████████████████████████   100.0%

```


 Last Updated on 29/10/2025 18:48:12 UTC
<!--END_SECTION:waka-->
