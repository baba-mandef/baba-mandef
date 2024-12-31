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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C352%20hrs%2044%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   16 hrs 39 mins      ████████████░░░░░░░░░░░░░   51.16% 
HTML                     15 hrs 41 mins      ████████████░░░░░░░░░░░░░   48.18% 
Text                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.49% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  32 hrs 33 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                32 hrs              ████████████████████████░   98.3% 
demo                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.16% 
default                  7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.39% 
hudim                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

💻 Operating System: 
Linux                    32 hrs 33 mins      █████████████████████████   100.0%

```


 Last Updated on 31/12/2024 18:40:44 UTC
<!--END_SECTION:waka-->
