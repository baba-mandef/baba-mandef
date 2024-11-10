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
HTML                     5 hrs 49 mins       ████████████░░░░░░░░░░░░░   47.85% 
Python                   5 hrs 36 mins       ███████████░░░░░░░░░░░░░░   46.1% 
CSS                      20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.75% 
Text                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.95% 
JavaScript               6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.88%

🔥 Editors: 
VS Code                  12 hrs 10 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    11 hrs 28 mins      ███████████████████████░░   94.22% 
rezolusoft.com           14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.04% 
ekilibre                 12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.74% 
api.abiodoun.dev         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.53% 
abiodoun.dev             3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.47%

💻 Operating System: 
Linux                    12 hrs 10 mins      █████████████████████████   100.0%

```


 Last Updated on 10/11/2024 18:49:21 UTC
<!--END_SECTION:waka-->
