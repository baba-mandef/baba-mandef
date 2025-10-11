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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C862%20hrs%2051%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    1 hr 4 mins         ████████████░░░░░░░░░░░░░   48.4% 
Python                   34 mins             ██████░░░░░░░░░░░░░░░░░░░   25.97% 
HTML                     22 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.88% 
Git Config               4 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.72% 
Markdown                 3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.7%

🔥 Editors: 
VS Code                  1 hr 9 mins         █████████████░░░░░░░░░░░░   51.77% 
GIMP                     39 mins             ███████░░░░░░░░░░░░░░░░░░   29.73% 
Notion                   24 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.1% 
Terminal                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.4%

💻 Operating System: 
Mac                      2 hrs 13 mins       █████████████████████████   100.0%

```


 Last Updated on 11/10/2025 18:40:09 UTC
<!--END_SECTION:waka-->
