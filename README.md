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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C437%20hrs%2027%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     27 hrs 6 mins       ██████████████░░░░░░░░░░░   56.33% 
Python                   18 hrs 26 mins      █████████░░░░░░░░░░░░░░░░   38.34% 
Gettext Catalog          1 hr 12 mins        ░░░░░░░░░░░░░░░░░░░░░░░░░   2.51% 
CSS                      31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.09% 
JavaScript               22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.77%

🔥 Editors: 
VS Code                  48 hrs 7 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 25 hrs 28 mins      █████████████░░░░░░░░░░░░   52.92% 
investioo                22 hrs 23 mins      ███████████░░░░░░░░░░░░░░   46.52% 
MULTI                    16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.55%

💻 Operating System: 
Linux                    48 hrs 7 mins       █████████████████████████   100.0%

```


 Last Updated on 17/01/2025 18:40:53 UTC
<!--END_SECTION:waka-->
