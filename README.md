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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C660%20hrs%2015%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 1 min         ███████████████████████░░   92.57% 
CSS                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.12% 
Python                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.08% 
JavaScript               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.75% 
JSON                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.47%

🔥 Editors: 
VS Code                  5 hrs 25 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    5 hrs 25 mins       █████████████████████████   100.0%

```


 Last Updated on 15/05/2025 18:47:21 UTC
<!--END_SECTION:waka-->
