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
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C459%20hrs%2020%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     25 hrs 26 mins      █████████████░░░░░░░░░░░░   54.43% 
Python                   19 hrs 24 mins      ██████████░░░░░░░░░░░░░░░   41.5% 
Gettext Catalog          1 hr 12 mins        ░░░░░░░░░░░░░░░░░░░░░░░░░   2.59% 
JavaScript               19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.69% 
Text                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5%

🔥 Editors: 
VS Code                  46 hrs 45 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 33 hrs 55 mins      ██████████████████░░░░░░░   72.56% 
investioo                12 hrs 15 mins      ██████░░░░░░░░░░░░░░░░░░░   26.21% 
MULTI                    34 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.22%

💻 Operating System: 
Linux                    46 hrs 45 mins      █████████████████████████   100.0%

```


 Last Updated on 19/01/2025 18:39:01 UTC
<!--END_SECTION:waka-->
