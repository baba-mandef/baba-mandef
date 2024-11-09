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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C208%20hrs%207%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     8 hrs 37 mins       ██████████████░░░░░░░░░░░   57.58% 
Python                   5 hrs 36 mins       █████████░░░░░░░░░░░░░░░░   37.44% 
CSS                      22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.5% 
Text                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.59% 
JavaScript               4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.53%

🔥 Editors: 
VS Code                  14 hrs 59 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    14 hrs 24 mins      ████████████████████████░   96.14% 
ekilibre                 12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.41% 
api.abiodoun.dev         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.24% 
rezolusoft.com           7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.82% 
abiodoun.dev             3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.38%

💻 Operating System: 
Linux                    14 hrs 59 mins      █████████████████████████   100.0%

```


 Last Updated on 09/11/2024 18:46:47 UTC
<!--END_SECTION:waka-->
