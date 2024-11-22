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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C227%20hrs%2014%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      5 hrs 39 mins       ███████░░░░░░░░░░░░░░░░░░   28.91% 
Python                   5 hrs 33 mins       ███████░░░░░░░░░░░░░░░░░░   28.42% 
HTML                     2 hrs 25 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.4% 
Text                     1 hr 35 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.18% 
Other                    1 hr 9 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   5.96%

🔥 Editors: 
VS Code                  19 hrs 32 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 10 hrs 37 mins      █████████████░░░░░░░░░░░░   54.33% 
kyff                     5 hrs 9 mins        ██████░░░░░░░░░░░░░░░░░░░   26.39% 
ekilibre-design.com      1 hr 13 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.3% 
hudim                    54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.66% 
blog_php                 40 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.42%

💻 Operating System: 
Linux                    19 hrs 32 mins      █████████████████████████   100.0%

```


 Last Updated on 22/11/2024 18:52:31 UTC
<!--END_SECTION:waka-->
