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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C210%20hrs%2021%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      2 hrs 30 mins       ██████████████░░░░░░░░░░░   56.05% 
Python                   45 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.03% 
HTML                     42 mins             ████░░░░░░░░░░░░░░░░░░░░░   15.92% 
JavaScript               13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.96% 
Text                     10 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.85%

🔥 Editors: 
VS Code                  4 hrs 28 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
esmblog                  2 hrs 30 mins       ██████████████░░░░░░░░░░░   56.27% 
rezolusoft.com           58 mins             █████░░░░░░░░░░░░░░░░░░░░   21.73% 
hudim                    39 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.67% 
ekilibre                 16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.97% 
api.abiodoun.dev         3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.35%

💻 Operating System: 
Linux                    4 hrs 28 mins       █████████████████████████   100.0%

```


 Last Updated on 14/11/2024 18:49:09 UTC
<!--END_SECTION:waka-->
