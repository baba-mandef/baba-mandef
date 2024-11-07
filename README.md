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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C202%20hrs%2048%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     10 hrs 28 mins      ███████████████░░░░░░░░░░   62.17% 
Python                   5 hrs 29 mins       ████████░░░░░░░░░░░░░░░░░   32.57% 
Text                     23 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.36% 
CSS                      22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22% 
JavaScript               4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.47%

🔥 Editors: 
VS Code                  16 hrs 50 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
hudim                    15 hrs 35 mins      ███████████████████████░░   92.56% 
rezolusoft.com           50 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.99% 
ekilibre                 12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.26% 
api.abiodoun.dev         8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.86% 
abiodoun.dev             3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34%

💻 Operating System: 
Linux                    16 hrs 50 mins      █████████████████████████   100.0%

```


 Last Updated on 07/11/2024 18:47:09 UTC
<!--END_SECTION:waka-->
