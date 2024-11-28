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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C243%20hrs%2059%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     6 hrs 5 mins        ███████░░░░░░░░░░░░░░░░░░   30.94% 
Python                   5 hrs 29 mins       ███████░░░░░░░░░░░░░░░░░░   27.91% 
PHP                      5 hrs 27 mins       ███████░░░░░░░░░░░░░░░░░░   27.79% 
CSS                      1 hr 21 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.91% 
JavaScript               51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.38%

🔥 Editors: 
VS Code                  19 hrs 39 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 11 hrs 30 mins      ██████████████░░░░░░░░░░░   58.55% 
kyff                     4 hrs 12 mins       █████░░░░░░░░░░░░░░░░░░░░   21.37% 
cse                      1 hr 52 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.53% 
tp                       1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.55% 
Sharify                  28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.42%

💻 Operating System: 
Linux                    19 hrs 39 mins      █████████████████████████   100.0%

```


 Last Updated on 28/11/2024 18:51:33 UTC
<!--END_SECTION:waka-->
