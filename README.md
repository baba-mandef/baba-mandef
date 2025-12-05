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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C924%20hrs%205%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 41 mins       ███████████░░░░░░░░░░░░░░   45.39% 
Python                   3 hrs 56 mins       ██████░░░░░░░░░░░░░░░░░░░   26.72% 
Other                    2 hrs 41 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.22% 
CSS                      1 hr 9 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   7.89% 
JavaScript               14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.69%

🔥 Editors: 
VS Code                  12 hrs 3 mins       ████████████████████░░░░░   81.77% 
GIMP                     1 hr 22 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.33% 
Terminal                 1 hr 18 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.89%

💻 Operating System: 
Mac                      14 hrs 44 mins      █████████████████████████   100.0%

```


 Last Updated on 05/12/2025 18:47:45 UTC
<!--END_SECTION:waka-->
