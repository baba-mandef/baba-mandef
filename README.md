###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'Name': 'Abiodoun PARAISO',
            'Stack': {
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'AskMe': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C193%20hrs%206%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-417%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     4 hrs 42 mins       █████████░░░░░░░░░░░░░░░░   37.7% 
JavaScript               3 hrs 25 mins       ██████░░░░░░░░░░░░░░░░░░░   27.44% 
Python                   2 hrs 24 mins       ████░░░░░░░░░░░░░░░░░░░░░   19.24% 
JSON                     54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.25% 
Text                     27 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.64%

🔥 Editors: 
VS Code                  12 hrs 29 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    4 hrs 44 mins       █████████░░░░░░░░░░░░░░░░   37.97% 
abiodoun.dev             4 hrs 39 mins       █████████░░░░░░░░░░░░░░░░   37.27% 
api.abiodoun.dev         2 hrs 10 mins       ████░░░░░░░░░░░░░░░░░░░░░   17.46% 
rezolusoft.com           54 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.3%

💻 Operating System: 
Linux                    12 hrs 29 mins      █████████████████████████   100.0%

```


 Last Updated on 03/11/2024 18:49:44 UTC
<!--END_SECTION:waka-->
