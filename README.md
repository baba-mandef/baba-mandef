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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C213%20hrs%2028%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      2 hrs 35 mins       █████████░░░░░░░░░░░░░░░░   35.62% 
Python                   1 hr 53 mins        ██████░░░░░░░░░░░░░░░░░░░   26.17% 
HTML                     1 hr 17 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.83% 
Text                     34 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.93% 
Bash                     20 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.66%

🔥 Editors: 
VS Code                  7 hrs 15 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 3 hrs 34 mins       ████████████░░░░░░░░░░░░░   49.15% 
esmblog                  2 hrs 35 mins       █████████░░░░░░░░░░░░░░░░   35.76% 
rezolusoft.com           49 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.27% 
hudim                    15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.55% 
api.abiodoun.dev         1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.27%

💻 Operating System: 
Linux                    7 hrs 15 mins       █████████████████████████   100.0%

```


 Last Updated on 17/11/2024 18:46:48 UTC
<!--END_SECTION:waka-->
