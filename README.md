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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C641%20hrs%2031%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     9 hrs 42 mins       ███████████████░░░░░░░░░░   62.21% 
JavaScript               3 hrs               ████░░░░░░░░░░░░░░░░░░░░░   19.3% 
Python                   2 hrs 45 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.65% 
CSS                      5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.63% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.13%

🔥 Editors: 
VS Code                  15 hrs 36 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        15 hrs 13 mins      ████████████████████████░   97.55% 
crypo.netlify.app        15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.63% 
interlin                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.64% 
trade                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

💻 Operating System: 
Linux                    15 hrs 36 mins      █████████████████████████   100.0%

```


 Last Updated on 18/04/2025 18:44:11 UTC
<!--END_SECTION:waka-->
