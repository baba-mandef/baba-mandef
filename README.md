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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C724%20hrs%2027%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 32 mins       ███████████░░░░░░░░░░░░░░   46.77% 
Python                   5 hrs 43 mins       ██████████░░░░░░░░░░░░░░░   41.01% 
CSS                      39 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.69% 
Text                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.66% 
Gettext Catalog          15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.9%

🔥 Editors: 
VS Code                  13 hrs 58 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    13 hrs 58 mins      █████████████████████████   100.0%

```


 Last Updated on 13/07/2025 18:46:40 UTC
<!--END_SECTION:waka-->
