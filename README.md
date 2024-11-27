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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C242%20hrs%2032%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      6 hrs 58 mins       █████████░░░░░░░░░░░░░░░░   37.61% 
HTML                     5 hrs 43 mins       ███████░░░░░░░░░░░░░░░░░░   30.85% 
Python                   3 hrs 27 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.62% 
CSS                      1 hr 23 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.49% 
JavaScript               35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15%

🔥 Editors: 
VS Code                  18 hrs 33 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 8 hrs 57 mins       ████████████░░░░░░░░░░░░░   48.26% 
kyff                     5 hrs 37 mins       ███████░░░░░░░░░░░░░░░░░░   30.35% 
cse                      1 hr 31 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.19% 
tp                       1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.95% 
blog_php                 40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.6%

💻 Operating System: 
Linux                    18 hrs 33 mins      █████████████████████████   100.0%

```


 Last Updated on 27/11/2024 18:50:28 UTC
<!--END_SECTION:waka-->
