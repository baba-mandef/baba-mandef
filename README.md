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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C769%20hrs%2041%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   13 hrs 9 mins       █████████████████░░░░░░░░   69.6% 
HTML                     4 hrs 30 mins       ██████░░░░░░░░░░░░░░░░░░░   23.87% 
Markdown                 28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.54% 
Bash                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.5% 
Git                      10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.94%

🔥 Editors: 
VS Code                  18 hrs 54 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      18 hrs 39 mins      ████████████████████████░   98.74% 
Linux                    14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.26%

```


 Last Updated on 14/08/2025 18:51:09 UTC
<!--END_SECTION:waka-->
