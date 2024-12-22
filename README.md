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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C304%20hrs%2041%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 47 mins       ██████████████████░░░░░░░   74.53% 
JavaScript               1 hr 42 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.56% 
HTML                     58 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.29% 
Text                     9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.28% 
Dart                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.79%

🔥 Editors: 
VS Code                  11 hrs 47 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 11 hrs 31 mins      ████████████████████████░   97.83% 
investioo                9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.37% 
ishiro                   5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.79%

💻 Operating System: 
Linux                    11 hrs 47 mins      █████████████████████████   100.0%

```


 Last Updated on 22/12/2024 18:39:14 UTC
<!--END_SECTION:waka-->
