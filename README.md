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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C779%20hrs%2037%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   12 hrs 47 mins      ███████████████████░░░░░░   79.0% 
HTML                     2 hrs 18 mins       ███░░░░░░░░░░░░░░░░░░░░░░   14.21% 
CSS                      32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.3% 
TOML                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.65% 
Git Config               8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.83%

🔥 Editors: 
VS Code                  16 hrs 11 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      16 hrs 8 mins       █████████████████████████   99.67% 
Linux                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.33%

```


 Last Updated on 19/08/2025 18:46:37 UTC
<!--END_SECTION:waka-->
