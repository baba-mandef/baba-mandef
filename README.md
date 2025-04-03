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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C619%20hrs%2018%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1338-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   4 hrs 28 mins       █████████████░░░░░░░░░░░░   51.97% 
HTML                     1 hr 47 mins        █████░░░░░░░░░░░░░░░░░░░░   20.71% 
JavaScript               1 hr                ███░░░░░░░░░░░░░░░░░░░░░░   11.75% 
Text                     42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.16% 
CSS                      36 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.12%

🔥 Editors: 
VS Code                  8 hrs 37 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        4 hrs 59 mins       ██████████████░░░░░░░░░░░   57.87% 
rezolusoft.com           2 hrs 15 mins       ██████░░░░░░░░░░░░░░░░░░░   26.28% 
api.checkupclimat.com    1 hr 14 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.34% 
dist                     6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.33% 
seomy                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

💻 Operating System: 
Linux                    8 hrs 37 mins       █████████████████████████   100.0%

```


 Last Updated on 03/04/2025 18:44:34 UTC
<!--END_SECTION:waka-->
