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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C251%20hrs%2013%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     8 hrs 8 mins        ███████████░░░░░░░░░░░░░░   45.16% 
Python                   7 hrs 9 mins        ██████████░░░░░░░░░░░░░░░   39.67% 
JavaScript               1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   7.18% 
CSS                      1 hr 12 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.68% 
Bash                     13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.29%

🔥 Editors: 
VS Code                  18 hrs 1 min        █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 16 hrs 8 mins       ██████████████████████░░░   89.6% 
cse                      1 hr 52 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.4%

💻 Operating System: 
Linux                    18 hrs 1 min        █████████████████████████   100.0%

```


 Last Updated on 01/12/2024 18:48:09 UTC
<!--END_SECTION:waka-->
