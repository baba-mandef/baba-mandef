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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C611%20hrs%2054%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1338-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     3 hrs 12 mins       █████████░░░░░░░░░░░░░░░░   37.95% 
CSS                      2 hrs 32 mins       ███████░░░░░░░░░░░░░░░░░░   30.01% 
Python                   1 hr 57 mins        █████░░░░░░░░░░░░░░░░░░░░   23.21% 
Text                     42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.42% 
Markdown                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

🔥 Editors: 
VS Code                  8 hrs 27 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           6 hrs 27 mins       ███████████████████░░░░░░   76.33% 
api.checkupclimat.com    1 hr 14 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.6% 
investioo-finance        45 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.89% 
seomy                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

💻 Operating System: 
Linux                    8 hrs 27 mins       █████████████████████████   100.0%

```


 Last Updated on 01/04/2025 18:45:43 UTC
<!--END_SECTION:waka-->
