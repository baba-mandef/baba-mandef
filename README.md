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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C819%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-5-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   14 hrs 53 mins      ████████████░░░░░░░░░░░░░   48.65% 
HTML                     10 hrs              ████████░░░░░░░░░░░░░░░░░   32.66% 
Other                    4 hrs 17 mins       ███░░░░░░░░░░░░░░░░░░░░░░   13.99% 
Image (svg)              44 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.42% 
CSS                      32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.77%

🔥 Editors: 
VS Code                  25 hrs 49 mins      █████████████████████░░░░   84.37% 
Terminal                 2 hrs 31 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   8.25% 
Notion                   59 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.22% 
Figma                    44 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.42% 
GIMP                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.71%

💻 Operating System: 
Mac                      30 hrs 37 mins      █████████████████████████   100.0%

```


 Last Updated on 28/08/2025 18:46:22 UTC
<!--END_SECTION:waka-->
