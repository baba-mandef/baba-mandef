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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C609%20hrs%2033%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1338-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     3 hrs 21 mins       ███████████░░░░░░░░░░░░░░   45.91% 
CSS                      2 hrs 32 mins       ████████░░░░░░░░░░░░░░░░░   34.69% 
Python                   1 hr 20 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.41% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.7% 
Markdown                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

🔥 Editors: 
VS Code                  7 hrs 19 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           6 hrs 46 mins       ███████████████████████░░   92.47% 
investioo-finance        32 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.33% 
seomy                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21%

💻 Operating System: 
Linux                    7 hrs 19 mins       █████████████████████████   100.0%

```


 Last Updated on 30/03/2025 18:41:41 UTC
<!--END_SECTION:waka-->
