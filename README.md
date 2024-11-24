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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C233%20hrs%2046%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      6 hrs 58 mins       ████████░░░░░░░░░░░░░░░░░   32.16% 
Python                   5 hrs 31 mins       ██████░░░░░░░░░░░░░░░░░░░   25.44% 
HTML                     3 hrs 36 mins       ████░░░░░░░░░░░░░░░░░░░░░   16.63% 
Other                    1 hr 12 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.54% 
Text                     1 hr 8 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.3%

🔥 Editors: 
VS Code                  21 hrs 41 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 10 hrs 59 mins      ████████████░░░░░░░░░░░░░   50.65% 
kyff                     5 hrs 37 mins       ██████░░░░░░░░░░░░░░░░░░░   25.95% 
tp                       1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.94% 
ekilibre-design.com      1 hr 13 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.68% 
hudim                    54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.2%

💻 Operating System: 
Linux                    21 hrs 41 mins      █████████████████████████   100.0%

```


 Last Updated on 24/11/2024 18:46:35 UTC
<!--END_SECTION:waka-->
