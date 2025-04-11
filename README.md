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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C629%20hrs%204%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     5 hrs 14 mins       █████████████████████░░░░   83.63% 
CSS                      34 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.24% 
JavaScript               19 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.1% 
Python                   7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.03%

🔥 Editors: 
VS Code                  6 hrs 16 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
api.checkupclimat.com    3 hrs 14 mins       █████████████░░░░░░░░░░░░   51.59% 
investioo-finance        2 hrs 34 mins       ██████████░░░░░░░░░░░░░░░   40.93% 
solak                    28 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.48%

💻 Operating System: 
Linux                    6 hrs 16 mins       █████████████████████████   100.0%

```


 Last Updated on 11/04/2025 18:44:51 UTC
<!--END_SECTION:waka-->
