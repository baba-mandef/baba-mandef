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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C947%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   2 hrs 28 mins       ██████████░░░░░░░░░░░░░░░   42.53% 
HTML                     1 hr 56 mins        ████████░░░░░░░░░░░░░░░░░   33.46% 
JavaScript               49 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.15% 
Other                    34 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.86%

🔥 Editors: 
VS Code                  5 hrs 14 mins       ██████████████████████░░░   90.14% 
Terminal                 34 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.86%

💻 Operating System: 
Mac                      5 hrs 49 mins       █████████████████████████   100.0%

```


 Last Updated on 30/12/2025 18:52:24 UTC
<!--END_SECTION:waka-->
