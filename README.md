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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C185%20hrs%2029%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-417%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   1 hr 31 mins        ████████░░░░░░░░░░░░░░░░░   32.56% 
JavaScript               1 hr 9 mins         ██████░░░░░░░░░░░░░░░░░░░   24.63% 
HTML                     38 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.72% 
JSON                     38 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.49% 
Text                     26 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.45%

🔥 Editors: 
VS Code                  4 hrs 41 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
abiodoun.dev             1 hr 45 mins        █████████░░░░░░░░░░░░░░░░   37.35% 
api.abiodoun.dev         1 hr 39 mins        ████████░░░░░░░░░░░░░░░░░   35.27% 
omural                   37 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.19% 
hudim                    29 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.51% 
rezolusoft.com           10 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.68%

💻 Operating System: 
Linux                    4 hrs 41 mins       █████████████████████████   100.0%

```


 Last Updated on 30/10/2024 18:49:01 UTC
<!--END_SECTION:waka-->
