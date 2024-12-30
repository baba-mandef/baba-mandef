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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C345%20hrs%2011%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     19 hrs 31 mins      █████████████░░░░░░░░░░░░   55.34% 
Python                   15 hrs 35 mins      ███████████░░░░░░░░░░░░░░   44.18% 
Text                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.33% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12% 
JavaScript               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  35 hrs 17 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                34 hrs 25 mins      ████████████████████████░   97.54% 
default                  29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.39% 
demo                     22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.07%

💻 Operating System: 
Linux                    35 hrs 17 mins      █████████████████████████   100.0%

```


 Last Updated on 30/12/2024 18:41:45 UTC
<!--END_SECTION:waka-->
