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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C354%20hrs%2023%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   20 hrs 16 mins      █████████████░░░░░░░░░░░░   52.1% 
HTML                     18 hrs 23 mins      ███████████░░░░░░░░░░░░░░   47.28% 
Text                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.41% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

🔥 Editors: 
VS Code                  38 hrs 54 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                38 hrs 23 mins      ████████████████████████░   98.66% 
demo                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.97% 
default                  5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.24% 
hudim                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

💻 Operating System: 
Linux                    38 hrs 54 mins      █████████████████████████   100.0%

```


 Last Updated on 01/01/2025 18:41:17 UTC
<!--END_SECTION:waka-->
