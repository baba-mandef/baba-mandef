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
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C684%20hrs%2013%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 12 mins       █████████████████░░░░░░░░   68.1% 
Markdown                 48 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.48% 
HTML                     40 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.82% 
TOML                     32 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.18% 
CSS                      22 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.88%

🔥 Editors: 
VS Code                  7 hrs 38 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    7 hrs 38 mins       █████████████████████████   100.0%

```


 Last Updated on 17/06/2025 18:48:52 UTC
<!--END_SECTION:waka-->
