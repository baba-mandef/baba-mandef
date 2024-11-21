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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C225%20hrs%2026%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   5 hrs 28 mins       █████████░░░░░░░░░░░░░░░░   35.81% 
HTML                     2 hrs 40 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.51% 
Text                     1 hr 35 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.45% 
PHP                      1 hr 35 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.4% 
Other                    1 hr 9 mins         ██░░░░░░░░░░░░░░░░░░░░░░░   7.6%

🔥 Editors: 
VS Code                  15 hrs 18 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 10 hrs 32 mins      █████████████████░░░░░░░░   68.87% 
kyff                     1 hr 25 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.33% 
ekilibre-design.com      1 hr 13 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.04% 
hudim                    1 hr 10 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.63% 
blog_php                 22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.45%

💻 Operating System: 
Linux                    15 hrs 18 mins      █████████████████████████   100.0%

```


 Last Updated on 21/11/2024 18:52:26 UTC
<!--END_SECTION:waka-->
