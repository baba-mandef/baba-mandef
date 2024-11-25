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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C237%20hrs%2014%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      6 hrs 58 mins       ███████░░░░░░░░░░░░░░░░░░   28.75% 
Python                   6 hrs 2 mins        ██████░░░░░░░░░░░░░░░░░░░   24.87% 
HTML                     5 hrs 50 mins       ██████░░░░░░░░░░░░░░░░░░░   24.05% 
Other                    1 hr 11 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   4.9% 
Text                     1 hr 5 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   4.52%

🔥 Editors: 
VS Code                  24 hrs 16 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 14 hrs 36 mins      ███████████████░░░░░░░░░░   60.22% 
kyff                     5 hrs 37 mins       █████░░░░░░░░░░░░░░░░░░░░   23.2% 
tp                       1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.31% 
hudim                    54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.75% 
blog_php                 40 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.75%

💻 Operating System: 
Linux                    24 hrs 16 mins      █████████████████████████   100.0%

```


 Last Updated on 25/11/2024 18:53:08 UTC
<!--END_SECTION:waka-->
