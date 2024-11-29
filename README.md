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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C246%20hrs%2054%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   7 hrs 28 mins       ██████████░░░░░░░░░░░░░░░   40.13% 
HTML                     7 hrs 20 mins       █████████░░░░░░░░░░░░░░░░   39.41% 
CSS                      1 hr 19 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.13% 
PHP                      1 hr 19 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.12% 
JavaScript               51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.63%

🔥 Editors: 
VS Code                  18 hrs 37 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 14 hrs 58 mins      ████████████████████░░░░░   80.38% 
cse                      1 hr 52 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.06% 
tp                       1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.92% 
kyff                     28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.54% 
html                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.1%

💻 Operating System: 
Linux                    18 hrs 37 mins      █████████████████████████   100.0%

```


 Last Updated on 29/11/2024 18:52:13 UTC
<!--END_SECTION:waka-->
