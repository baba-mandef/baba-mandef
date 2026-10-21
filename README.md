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
![Code Time](http://img.shields.io/badge/Code%20Time-2%2C143%20hrs%2048%20mins-blue?style=flat)

![AI Code Time](http://img.shields.io/badge/AI%20Code%20Time-2%20hrs%2020%20mins-blue?style=flat)

![Profile Views](http://img.shields.io/badge/Profile%20Views-3-blue?style=flat)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-4.83%20million%20lines%20of%20code-blue?style=flat)

**🐱 My GitHub Data** 

> 📦 181.7 kB Used in GitHub's Storage 
 > 
> 🏆 472 Contributions in the Year 2026
 > 
> 💼 Opted to Hire
 > 
> 📜 31 Public Repositories 
 > 
> 🔑 6 Private Repositories 
 > 
📊 **This Week I Spent My Time On** 

```text
🕑︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   5 hrs 10 mins       ████████████████████████░   96.65 % 
Image (svg)              7 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   02.43 % 
Other                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   00.92 % 

🔥 Editors: 
VS Code                  5 hrs 10 mins       ████████████████████████░   96.65 % 
Figma                    7 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   02.43 % 
Terminal                 2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   00.92 % 

💻 Operating System: 
Mac                      5 hrs 21 mins       █████████████████████████   100.00 % 
```

🤖 **AI Coding This Week** 

```text
No AI Coding Activity Tracked This Week
```


 Last Updated on 21/10/2026 21:56:13 UTC
<!--END_SECTION:waka-->
