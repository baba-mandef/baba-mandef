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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C212%20hrs%2014%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      2 hrs 35 mins       ████████████░░░░░░░░░░░░░   48.43% 
HTML                     1 hr 9 mins         █████░░░░░░░░░░░░░░░░░░░░   21.75% 
Python                   58 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.29% 
JavaScript               13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.16% 
Text                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.38%

🔥 Editors: 
VS Code                  5 hrs 20 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
esmblog                  2 hrs 35 mins       ████████████░░░░░░░░░░░░░   48.61% 
ekilibre                 1 hr 29 mins        ███████░░░░░░░░░░░░░░░░░░   28.0% 
rezolusoft.com           58 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.19% 
hudim                    15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.83% 
api.abiodoun.dev         1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36%

💻 Operating System: 
Linux                    5 hrs 20 mins       █████████████████████████   100.0%

```


 Last Updated on 16/11/2024 18:46:30 UTC
<!--END_SECTION:waka-->
