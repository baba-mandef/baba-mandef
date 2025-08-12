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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C761%20hrs%2023%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   14 hrs 27 mins      ███████████████████░░░░░░   75.57% 
HTML                     3 hrs 37 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.95% 
Markdown                 28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.5% 
Git                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.93% 
Bash                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.91%

🔥 Editors: 
VS Code                  19 hrs 8 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      18 hrs 54 mins      ████████████████████████░   98.76% 
Linux                    14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.24%

```


 Last Updated on 12/08/2025 18:51:04 UTC
<!--END_SECTION:waka-->
