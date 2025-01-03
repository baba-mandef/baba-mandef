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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C360%20hrs%209%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   12 hrs 54 mins      ████████████░░░░░░░░░░░░░   50.65% 
HTML                     12 hrs 26 mins      ████████████░░░░░░░░░░░░░   48.8% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.21% 
Text                     2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.18% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.09%

🔥 Editors: 
VS Code                  25 hrs 29 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
investioo                21 hrs 19 mins      █████████████████████░░░░   83.63% 
ekilibre                 3 hrs 52 mins       ███░░░░░░░░░░░░░░░░░░░░░░   15.2% 
demo                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.98% 
hudim                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

💻 Operating System: 
Linux                    25 hrs 29 mins      █████████████████████████   100.0%

```


 Last Updated on 03/01/2025 18:41:43 UTC
<!--END_SECTION:waka-->
