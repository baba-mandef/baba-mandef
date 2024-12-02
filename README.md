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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C255%20hrs%2019%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     6 hrs 52 mins       ███████████░░░░░░░░░░░░░░   45.64% 
Python                   5 hrs 39 mins       █████████░░░░░░░░░░░░░░░░   37.6% 
CSS                      1 hr 10 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.77% 
JavaScript               1 hr 7 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   7.45% 
Bash                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.54%

🔥 Editors: 
VS Code                  15 hrs 4 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 13 hrs 11 mins      ██████████████████████░░░   87.56% 
cse                      1 hr 52 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.44%

💻 Operating System: 
Linux                    15 hrs 4 mins       █████████████████████████   100.0%

```


 Last Updated on 02/12/2024 18:53:29 UTC
<!--END_SECTION:waka-->
