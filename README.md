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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C637%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     11 hrs 12 mins      ████████████████░░░░░░░░░   65.45% 
JavaScript               3 hrs 6 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.17% 
Python                   2 hrs 40 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.61% 
CSS                      5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.12%

🔥 Editors: 
VS Code                  17 hrs 7 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        15 hrs 13 mins      ██████████████████████░░░   88.94% 
api.checkupclimat.com    1 hr 31 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.94% 
crypo.netlify.app        15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.49% 
solak                    4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.48% 
trade                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

💻 Operating System: 
Linux                    17 hrs 7 mins       █████████████████████████   100.0%

```


 Last Updated on 17/04/2025 18:44:57 UTC
<!--END_SECTION:waka-->
