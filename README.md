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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C730%20hrs%201%20min-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
JavaScript               6 hrs 16 mins       █████████████░░░░░░░░░░░░   53.78% 
Python                   2 hrs 52 mins       ██████░░░░░░░░░░░░░░░░░░░   24.62% 
HTML                     2 hrs 12 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.91% 
Text                     18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.67% 
TypeScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🔥 Editors: 
VS Code                  11 hrs 40 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    11 hrs 40 mins      █████████████████████████   100.0%

```


 Last Updated on 16/07/2025 18:52:03 UTC
<!--END_SECTION:waka-->
