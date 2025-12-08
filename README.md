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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C926%20hrs%2059%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     8 hrs 39 mins       ██████████████░░░░░░░░░░░   56.85% 
Python                   4 hrs 15 mins       ███████░░░░░░░░░░░░░░░░░░   27.96% 
Other                    1 hr                █░░░░░░░░░░░░░░░░░░░░░░░░   6.58% 
CSS                      40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.44% 
JavaScript               28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.07%

🔥 Editors: 
VS Code                  14 hrs 12 mins      ███████████████████████░░   93.42% 
GIMP                     54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.93% 
Terminal                 5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.65%

💻 Operating System: 
Mac                      15 hrs 12 mins      █████████████████████████   100.0%

```


 Last Updated on 08/12/2025 18:51:12 UTC
<!--END_SECTION:waka-->
