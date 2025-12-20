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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C940%20hrs%2049%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     6 hrs 34 mins       █████████████░░░░░░░░░░░░   54.78% 
Python                   4 hrs 22 mins       █████████░░░░░░░░░░░░░░░░   36.48% 
Bash                     30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.24% 
JavaScript               14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.97% 
Image (svg)              12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.74%

🔥 Editors: 
VS Code                  11 hrs 42 mins      ████████████████████████░   97.63% 
Figma                    12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.74% 
Terminal                 4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.63%

💻 Operating System: 
Mac                      11 hrs 59 mins      █████████████████████████   100.0%

```


 Last Updated on 20/12/2025 18:45:20 UTC
<!--END_SECTION:waka-->
