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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C609%20hrs%206%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     3 hrs 55 mins       ████████████░░░░░░░░░░░░░   47.97% 
Python                   2 hrs 8 mins        ██████░░░░░░░░░░░░░░░░░░░   26.14% 
CSS                      1 hr 55 mins        ██████░░░░░░░░░░░░░░░░░░░   23.54% 
JavaScript               7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.62% 
Text                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.63%

🔥 Editors: 
VS Code                  8 hrs 11 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           4 hrs 30 mins       █████████████░░░░░░░░░░░░   55.07% 
investioo-finance        3 hrs 25 mins       ██████████░░░░░░░░░░░░░░░   41.85% 
interlin                 7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.58% 
abiodoun.dev             6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.33% 
dist                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17%

💻 Operating System: 
Linux                    8 hrs 11 mins       █████████████████████████   100.0%

```


 Last Updated on 27/03/2025 18:44:57 UTC
<!--END_SECTION:waka-->
