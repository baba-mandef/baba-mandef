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
                       'languages': ['Python', 'JS', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'English', 'French'],
                       'tools': ['Django', 'React', 'Flet', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C928%20hrs%2027%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 21 mins       ████████████████░░░░░░░░░   64.36% 
Python                   2 hrs 35 mins       ██████░░░░░░░░░░░░░░░░░░░   26.19% 
Other                    19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.36% 
JavaScript               13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.2% 
Bash                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.7%

🔥 Editors: 
VS Code                  9 hrs 29 mins       ████████████████████████░   95.98% 
GIMP                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.25% 
Figma                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.66% 
Terminal                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

💻 Operating System: 
Mac                      9 hrs 52 mins       █████████████████████████   100.0%

```


 Last Updated on 11/12/2025 18:52:51 UTC
<!--END_SECTION:waka-->
