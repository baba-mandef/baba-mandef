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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C928%20hrs%2056%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     2 hrs 17 mins       █████████████████░░░░░░░░   68.36% 
Python                   31 mins             ███░░░░░░░░░░░░░░░░░░░░░░   15.39% 
Other                    28 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.31% 
Image (svg)              3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.94%

🔥 Editors: 
VS Code                  2 hrs 48 mins       █████████████████████░░░░   83.75% 
GIMP                     19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.44% 
Terminal                 9 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.86% 
Figma                    3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.94%

💻 Operating System: 
Mac                      3 hrs 21 mins       █████████████████████████   100.0%

```


 Last Updated on 13/12/2025 18:45:33 UTC
<!--END_SECTION:waka-->
