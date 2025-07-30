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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C744%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   9 hrs 59 mins       ████████████████████░░░░░   80.92% 
HTML                     1 hr 40 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.6% 
Text                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.06% 
Git Config               12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.75% 
Bash                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.56%

🔥 Editors: 
VS Code                  12 hrs 20 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      12 hrs 9 mins       ████████████████████████░   98.49% 
Linux                    11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.51%

```


 Last Updated on 30/07/2025 18:53:02 UTC
<!--END_SECTION:waka-->
