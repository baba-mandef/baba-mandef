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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C257%20hrs%2013%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   10 hrs 44 mins      █████████████░░░░░░░░░░░░   53.1% 
HTML                     6 hrs 58 mins       ████████░░░░░░░░░░░░░░░░░   34.45% 
CSS                      1 hr 10 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.78% 
JavaScript               1 hr 6 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.51% 
Bash                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.15%

🔥 Editors: 
VS Code                  20 hrs 13 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 18 hrs 24 mins      ██████████████████████░░░   91.03% 
cse                      1 hr 48 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.97%

💻 Operating System: 
Linux                    20 hrs 13 mins      █████████████████████████   100.0%

```


 Last Updated on 03/12/2024 18:50:15 UTC
<!--END_SECTION:waka-->
