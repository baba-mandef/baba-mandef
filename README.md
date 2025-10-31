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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C868%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Other                    2 hrs 35 mins       ██████████████████░░░░░░░   72.02% 
Python                   29 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.81% 
HTML                     20 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.61% 
Markdown                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.78% 
Git Config               2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.12%

🔥 Editors: 
GIMP                     1 hr 56 mins        █████████████░░░░░░░░░░░░   54.03% 
VS Code                  1 hr                ███████░░░░░░░░░░░░░░░░░░   27.98% 
Terminal                 38 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.99%

💻 Operating System: 
Mac                      3 hrs 36 mins       █████████████████████████   100.0%

```


 Last Updated on 31/10/2025 18:47:57 UTC
<!--END_SECTION:waka-->
