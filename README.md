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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C643%20hrs%2022%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     4 hrs 6 mins        █████████████░░░░░░░░░░░░   54.58% 
JavaScript               2 hrs 34 mins       ████████░░░░░░░░░░░░░░░░░   34.14% 
Python                   42 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.41% 
CSS                      8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.88%

🔥 Editors: 
VS Code                  7 hrs 31 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        7 hrs 10 mins       ███████████████████████░░   95.38% 
interlin                 12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.85% 
crypo.netlify.app        7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.77%

💻 Operating System: 
Linux                    7 hrs 31 mins       █████████████████████████   100.0%

```


 Last Updated on 22/04/2025 18:45:43 UTC
<!--END_SECTION:waka-->
