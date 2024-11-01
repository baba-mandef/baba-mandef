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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C190%20hrs%2034%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-417%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               3 hrs 23 mins       █████████░░░░░░░░░░░░░░░░   35.59% 
Python                   2 hrs 13 mins       █████░░░░░░░░░░░░░░░░░░░░   23.32% 
HTML                     1 hr 41 mins        ████░░░░░░░░░░░░░░░░░░░░░   17.75% 
JSON                     54 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.51% 
Text                     38 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.81%

🔥 Editors: 
VS Code                  9 hrs 31 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
abiodoun.dev             4 hrs 38 mins       ████████████░░░░░░░░░░░░░   48.71% 
api.abiodoun.dev         1 hr 51 mins        █████░░░░░░░░░░░░░░░░░░░░   19.58% 
hudim                    1 hr 30 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.87% 
rezolusoft.com           53 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.34% 
omural                   37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.5%

💻 Operating System: 
Linux                    9 hrs 31 mins       █████████████████████████   100.0%

```


 Last Updated on 01/11/2024 18:48:25 UTC
<!--END_SECTION:waka-->
