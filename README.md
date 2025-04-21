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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C642%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     4 hrs 45 mins       █████████████░░░░░░░░░░░░   55.45% 
JavaScript               2 hrs 52 mins       ████████░░░░░░░░░░░░░░░░░   33.59% 
Python                   47 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.24% 
CSS                      8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.65% 
DIGITAL Command Language 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

🔥 Editors: 
VS Code                  8 hrs 34 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        8 hrs 13 mins       ████████████████████████░   95.93% 
interlin                 12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.5% 
crypo.netlify.app        7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.55% 
trade                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

💻 Operating System: 
Linux                    8 hrs 34 mins       █████████████████████████   100.0%

```


 Last Updated on 21/04/2025 18:45:25 UTC
<!--END_SECTION:waka-->
