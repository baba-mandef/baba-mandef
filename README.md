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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C208%20hrs%2036%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     3 hrs 6 mins        ██████████░░░░░░░░░░░░░░░   40.91% 
Python                   2 hrs 46 mins       █████████░░░░░░░░░░░░░░░░   36.56% 
PHP                      58 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.92% 
Text                     21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.8% 
JavaScript               13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.93%

🔥 Editors: 
VS Code                  7 hrs 34 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    4 hrs 50 mins       ████████████████░░░░░░░░░   63.8% 
rezolusoft.com           1 hr 4 mins         ███░░░░░░░░░░░░░░░░░░░░░░   14.13% 
esmblog                  59 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.05% 
ekilibre                 28 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.32% 
api.abiodoun.dev         12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.7%

💻 Operating System: 
Linux                    7 hrs 34 mins       █████████████████████████   100.0%

```


 Last Updated on 13/11/2024 18:48:50 UTC
<!--END_SECTION:waka-->
