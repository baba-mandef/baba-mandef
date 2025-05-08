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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C655%20hrs%2038%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 22 mins       ██████████████░░░░░░░░░░░   57.99% 
JavaScript               2 hrs 32 mins       ██████░░░░░░░░░░░░░░░░░░░   27.41% 
Python                   1 hr 10 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.58% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.36% 
YAML                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.66%

🔥 Editors: 
VS Code                  9 hrs 16 mins       █████████████████████████   100.0%

💻 Operating System: 
Linux                    9 hrs 16 mins       █████████████████████████   100.0%

```


 Last Updated on 08/05/2025 18:46:55 UTC
<!--END_SECTION:waka-->
