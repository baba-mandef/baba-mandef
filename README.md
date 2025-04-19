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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C642%20hrs%2046%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 27 mins       ██████████████░░░░░░░░░░░   55.69% 
JavaScript               2 hrs 51 mins       ██████░░░░░░░░░░░░░░░░░░░   24.69% 
Python                   2 hrs 8 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.56% 
CSS                      5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.84% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18%

🔥 Editors: 
VS Code                  11 hrs 35 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo-finance        11 hrs 19 mins      ████████████████████████░   97.71% 
crypo.netlify.app        8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.18% 
interlin                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.87% 
trade                    1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.24%

💻 Operating System: 
Linux                    11 hrs 35 mins      █████████████████████████   100.0%

```


 Last Updated on 19/04/2025 18:41:37 UTC
<!--END_SECTION:waka-->
