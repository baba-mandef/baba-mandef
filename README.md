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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C217%20hrs%2053%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   4 hrs 50 mins       ████████░░░░░░░░░░░░░░░░░   32.74% 
HTML                     3 hrs 9 mins        █████░░░░░░░░░░░░░░░░░░░░   21.29% 
PHP                      2 hrs 35 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.47% 
Text                     1 hr 42 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   11.49% 
YAML                     54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.12%

🔥 Editors: 
VS Code                  14 hrs 47 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 8 hrs 56 mins       ███████████████░░░░░░░░░░   60.41% 
esmblog                  2 hrs 35 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.54% 
ekilibre-design.com      1 hr 13 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   8.32% 
hudim                    1 hr 10 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.89% 
rezolusoft.com           51 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.83%

💻 Operating System: 
Linux                    14 hrs 47 mins      █████████████████████████   100.0%

```


 Last Updated on 19/11/2024 18:49:50 UTC
<!--END_SECTION:waka-->
