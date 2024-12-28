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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C332%20hrs%2020%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     18 hrs 16 mins      ██████████████░░░░░░░░░░░   55.57% 
Python                   14 hrs 13 mins      ██████████░░░░░░░░░░░░░░░   43.24% 
Text                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.81% 
JavaScript               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

🔥 Editors: 
VS Code                  32 hrs 53 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                30 hrs 10 mins      ███████████████████████░░   91.76% 
ekilibre                 1 hr 52 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.72% 
default                  35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.8% 
demo                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.71%

💻 Operating System: 
Linux                    32 hrs 53 mins      █████████████████████████   100.0%

```


 Last Updated on 28/12/2024 18:39:50 UTC
<!--END_SECTION:waka-->
