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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C741%20hrs%2029%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   8 hrs 20 mins       █████████████████████░░░░   84.67% 
HTML                     50 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.54% 
Text                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.59% 
Git Config               12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.19% 
Bash                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95%

🔥 Editors: 
VS Code                  9 hrs 51 mins       █████████████████████████   100.0%

💻 Operating System: 
Mac                      9 hrs 39 mins       ████████████████████████░   98.11% 
Linux                    11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.89%

```


 Last Updated on 28/07/2025 18:53:40 UTC
<!--END_SECTION:waka-->
