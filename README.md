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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C787%20hrs%2027%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   10 hrs 46 mins      █████████████████░░░░░░░░   71.4% 
HTML                     3 hrs 15 mins       █████░░░░░░░░░░░░░░░░░░░░   21.56% 
CSS                      43 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.78% 
TOML                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.77% 
Markdown                 2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.27%

🔥 Editors: 
VS Code                  15 hrs 6 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      15 hrs 2 mins       █████████████████████████   99.65% 
Linux                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.35%

```


 Last Updated on 20/08/2025 18:48:11 UTC
<!--END_SECTION:waka-->
