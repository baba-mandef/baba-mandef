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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C187%20hrs%2029%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-417%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               3 hrs 23 mins       ███████████░░░░░░░░░░░░░░   43.51% 
Python                   1 hr 44 mins        █████░░░░░░░░░░░░░░░░░░░░   22.3% 
JSON                     54 mins             ███░░░░░░░░░░░░░░░░░░░░░░   11.62% 
HTML                     38 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.27% 
Text                     26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.69%

🔥 Editors: 
VS Code                  7 hrs 47 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
abiodoun.dev             4 hrs 38 mins       ███████████████░░░░░░░░░░   59.56% 
api.abiodoun.dev         1 hr 51 mins        ██████░░░░░░░░░░░░░░░░░░░   23.93% 
omural                   37 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.95% 
hudim                    29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.34% 
rezolusoft.com           10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22%

💻 Operating System: 
Linux                    7 hrs 47 mins       █████████████████████████   100.0%

```


 Last Updated on 31/10/2024 18:51:30 UTC
<!--END_SECTION:waka-->
