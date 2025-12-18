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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C939%20hrs%2051%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   3 hrs 9 mins        ███████████████░░░░░░░░░░   61.42% 
HTML                     1 hr 22 mins        ██████░░░░░░░░░░░░░░░░░░░   26.92% 
Bash                     25 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.28% 
Other                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.0% 
Text                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.39%

🔥 Editors: 
VS Code                  4 hrs 58 mins       ████████████████████████░   97.0% 
Terminal                 9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.0%

💻 Operating System: 
Mac                      5 hrs 8 mins        █████████████████████████   100.0%

```


 Last Updated on 18/12/2025 18:52:46 UTC
<!--END_SECTION:waka-->
