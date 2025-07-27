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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C738%20hrs%2028%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 7 mins        ███████████████████████░░   93.44% 
Text                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.93% 
Bash                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.16% 
Git Config               6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.18% 
HTML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23%

🔥 Editors: 
VS Code                  8 hrs 41 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      8 hrs 30 mins       ████████████████████████░   97.86% 
Linux                    11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.14%

```


 Last Updated on 27/07/2025 18:49:36 UTC
<!--END_SECTION:waka-->
