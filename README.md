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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C215%20hrs%2032%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   3 hrs 2 mins        ████████░░░░░░░░░░░░░░░░░   31.87% 
PHP                      2 hrs 35 mins       ██████░░░░░░░░░░░░░░░░░░░   27.04% 
HTML                     2 hrs 4 mins        █████░░░░░░░░░░░░░░░░░░░░   21.64% 
Text                     37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.56% 
YAML                     31 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.5%

🔥 Editors: 
VS Code                  9 hrs 33 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 4 hrs 51 mins       ████████████░░░░░░░░░░░░░   50.78% 
esmblog                  2 hrs 35 mins       ██████░░░░░░░░░░░░░░░░░░░   27.15% 
rezolusoft.com           1 hr 1 min          ██░░░░░░░░░░░░░░░░░░░░░░░   10.79% 
ekilibre-design.com      48 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.38% 
hudim                    15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.7%

💻 Operating System: 
Linux                    9 hrs 33 mins       █████████████████████████   100.0%

```


 Last Updated on 18/11/2024 18:53:06 UTC
<!--END_SECTION:waka-->
