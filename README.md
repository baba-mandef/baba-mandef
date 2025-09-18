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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C854%20hrs%2040%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   11 hrs 58 mins      ██████████████████░░░░░░░   74.71% 
Other                    2 hrs 9 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.49% 
Image (svg)              1 hr 11 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.41% 
HTML                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.28% 
TOML                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.0%

🔥 Editors: 
VS Code                  12 hrs 41 mins      ███████████████████░░░░░░   79.11% 
Figma                    1 hr 11 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.41% 
GIMP                     1 hr 9 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   7.19% 
Terminal                 1 hr                █░░░░░░░░░░░░░░░░░░░░░░░░   6.29%

💻 Operating System: 
Mac                      16 hrs 2 mins       █████████████████████████   100.0%

```


 Last Updated on 18/09/2025 18:45:53 UTC
<!--END_SECTION:waka-->
