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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C250%20hrs%2025%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   8 hrs               ███████████░░░░░░░░░░░░░░   46.04% 
HTML                     7 hrs 20 mins       ██████████░░░░░░░░░░░░░░░   42.19% 
CSS                      53 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.14% 
JavaScript               51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.96% 
Bash                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.42%

🔥 Editors: 
VS Code                  17 hrs 22 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 15 hrs 30 mins      ██████████████████████░░░   89.22% 
cse                      1 hr 52 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.78%

💻 Operating System: 
Linux                    17 hrs 22 mins      █████████████████████████   100.0%

```


 Last Updated on 30/11/2024 18:47:30 UTC
<!--END_SECTION:waka-->
