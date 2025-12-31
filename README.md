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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C951%20hrs%2032%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 4 mins        ██████████░░░░░░░░░░░░░░░   40.37% 
HTML                     1 hr 58 mins        █████████░░░░░░░░░░░░░░░░   38.27% 
JavaScript               57 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.63% 
Other                    8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.72%

🔥 Editors: 
VS Code                  5 hrs               ████████████████████████░   97.28% 
Terminal                 8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.72%

💻 Operating System: 
Mac                      5 hrs 9 mins        █████████████████████████   100.0%

```


 Last Updated on 31/12/2025 18:49:42 UTC
<!--END_SECTION:waka-->
