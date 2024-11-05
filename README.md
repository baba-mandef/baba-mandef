###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'Name': 'Abiodoun PARAISO',
            'Stack': {
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'AskMe': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C198%20hrs%2024%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     6 hrs 54 mins       ███████████░░░░░░░░░░░░░░   43.88% 
JavaScript               3 hrs 29 mins       █████░░░░░░░░░░░░░░░░░░░░   22.16% 
Python                   3 hrs 22 mins       █████░░░░░░░░░░░░░░░░░░░░   21.42% 
JSON                     54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.8% 
CSS                      21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.26%

🔥 Editors: 
VS Code                  15 hrs 43 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    9 hrs 51 mins       ███████████████░░░░░░░░░░   62.61% 
abiodoun.dev             4 hrs 42 mins       ███████░░░░░░░░░░░░░░░░░░   29.97% 
rezolusoft.com           45 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.86% 
api.abiodoun.dev         24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.57%

💻 Operating System: 
Linux                    15 hrs 43 mins      █████████████████████████   100.0%

```


 Last Updated on 05/11/2024 18:49:19 UTC
<!--END_SECTION:waka-->
