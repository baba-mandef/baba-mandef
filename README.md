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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C231%20hrs%2047%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      6 hrs 58 mins       ████████░░░░░░░░░░░░░░░░░   34.36% 
Python                   4 hrs 53 mins       ██████░░░░░░░░░░░░░░░░░░░   24.06% 
HTML                     2 hrs 15 mins       ██░░░░░░░░░░░░░░░░░░░░░░░   11.13% 
Text                     1 hr 32 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.61% 
Other                    1 hr 9 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.74%

🔥 Editors: 
VS Code                  20 hrs 18 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 9 hrs 36 mins       ███████████░░░░░░░░░░░░░░   47.28% 
kyff                     5 hrs 37 mins       ███████░░░░░░░░░░░░░░░░░░   27.73% 
tp                       1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.35% 
ekilibre-design.com      1 hr 13 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.07% 
hudim                    54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.48%

💻 Operating System: 
Linux                    20 hrs 18 mins      █████████████████████████   100.0%

```


 Last Updated on 23/11/2024 18:47:20 UTC
<!--END_SECTION:waka-->
