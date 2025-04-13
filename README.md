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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C634%20hrs%2043%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     7 hrs 9 mins        ██████████████████░░░░░░░   74.38% 
Python                   1 hr 47 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.65% 
CSS                      24 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.28% 
JavaScript               15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.6% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

🔥 Editors: 
VS Code                  9 hrs 37 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        6 hrs 58 mins       ██████████████████░░░░░░░   72.51% 
api.checkupclimat.com    2 hrs 24 mins       ██████░░░░░░░░░░░░░░░░░░░   25.06% 
crypo.netlify.app        7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.26% 
solak                    6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.17%

💻 Operating System: 
Linux                    9 hrs 37 mins       █████████████████████████   100.0%

```


 Last Updated on 13/04/2025 18:42:06 UTC
<!--END_SECTION:waka-->
