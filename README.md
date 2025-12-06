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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C920%20hrs%2015%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     10 hrs 14 mins      ██████████████░░░░░░░░░░░   59.16% 
Python                   3 hrs 47 mins       █████░░░░░░░░░░░░░░░░░░░░   21.88% 
Other                    1 hr 28 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.57% 
CSS                      1 hr 9 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   6.72% 
JavaScript               28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.7%

🔥 Editors: 
VS Code                  15 hrs 49 mins      ██████████████████████░░░   91.43% 
GIMP                     1 hr 22 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.97% 
Terminal                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.6%

💻 Operating System: 
Mac                      17 hrs 18 mins      █████████████████████████   100.0%

```


 Last Updated on 06/12/2025 18:45:24 UTC
<!--END_SECTION:waka-->
