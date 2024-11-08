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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C207%20hrs%2026%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     9 hrs 24 mins       ███████████████░░░░░░░░░░   59.65% 
Python                   5 hrs 36 mins       █████████░░░░░░░░░░░░░░░░   35.61% 
CSS                      22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.37% 
Text                     14 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.51% 
JavaScript               4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.5%

🔥 Editors: 
VS Code                  15 hrs 45 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    15 hrs 11 mins      ████████████████████████░   96.33% 
ekilibre                 12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.35% 
api.abiodoun.dev         11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.18% 
rezolusoft.com           7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.78% 
abiodoun.dev             3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36%

💻 Operating System: 
Linux                    15 hrs 45 mins      █████████████████████████   100.0%

```


 Last Updated on 08/11/2024 18:49:31 UTC
<!--END_SECTION:waka-->
