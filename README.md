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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C810%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   18 hrs 2 mins       ██████████████░░░░░░░░░░░   56.97% 
HTML                     11 hrs 45 mins      █████████░░░░░░░░░░░░░░░░   37.1% 
CSS                      51 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.72% 
Other                    45 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.39% 
Image (svg)              9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52%

🔥 Editors: 
VS Code                  30 hrs 49 mins      ████████████████████████░   97.33% 
Notion                   25 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.34% 
Terminal                 14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.75% 
Figma                    9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52% 
Notes                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

💻 Operating System: 
Mac                      31 hrs 40 mins      █████████████████████████   100.0%

```


 Last Updated on 23/08/2025 18:43:16 UTC
<!--END_SECTION:waka-->
