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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C758%20hrs%2014%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   12 hrs 34 mins      █████████████████████░░░░   87.25% 
HTML                     58 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.77% 
Markdown                 28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.33% 
Git                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.24% 
JavaScript               4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.47%

🔥 Editors: 
VS Code                  14 hrs 24 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      14 hrs 11 mins      ████████████████████████░   98.45% 
Linux                    13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55%

```


 Last Updated on 11/08/2025 18:52:47 UTC
<!--END_SECTION:waka-->
