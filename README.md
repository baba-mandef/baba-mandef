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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C201%20hrs%2013%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     8 hrs 4 mins        █████████████░░░░░░░░░░░░   52.82% 
Python                   3 hrs 40 mins       ██████░░░░░░░░░░░░░░░░░░░   24.08% 
JavaScript               2 hrs 18 mins       ███░░░░░░░░░░░░░░░░░░░░░░   15.11% 
CSS                      21 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.32% 
JSON                     16 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.82%

🔥 Editors: 
VS Code                  15 hrs 17 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    11 hrs 24 mins      ██████████████████░░░░░░░   74.56% 
abiodoun.dev             2 hrs 56 mins       ████░░░░░░░░░░░░░░░░░░░░░   19.24% 
rezolusoft.com           44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.84% 
api.abiodoun.dev         12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.36%

💻 Operating System: 
Linux                    15 hrs 17 mins      █████████████████████████   100.0%

```


 Last Updated on 06/11/2024 18:51:11 UTC
<!--END_SECTION:waka-->
