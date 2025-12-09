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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C926%20hrs%2025%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
HTML                     9 hrs 27 mins       ██████████████░░░░░░░░░░░   59.0% 
Python                   4 hrs 15 mins       ██████░░░░░░░░░░░░░░░░░░░   26.53% 
Other                    1 hr                █░░░░░░░░░░░░░░░░░░░░░░░░   6.29% 
CSS                      40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.21% 
JavaScript               28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.91%

🔥 Editors: 
VS Code                  15 hrs 1 min        ███████████████████████░░   93.71% 
GIMP                     54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.63% 
Terminal                 6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.66%

💻 Operating System: 
Mac                      16 hrs 1 min        █████████████████████████   100.0%

```


 Last Updated on 09/12/2025 18:49:26 UTC
<!--END_SECTION:waka-->
