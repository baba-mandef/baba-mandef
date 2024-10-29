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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C183%20hrs%2034%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   1 hr 27 mins        █████████████░░░░░░░░░░░░   53.73% 
HTML                     38 mins             ██████░░░░░░░░░░░░░░░░░░░   23.66% 
Text                     26 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.29% 
CSS                      7 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   4.34% 
SQL                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.97%

🔥 Editors: 
VS Code                  2 hrs 43 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
api.abiodoun.dev         1 hr 27 mins        █████████████░░░░░░░░░░░░   53.66% 
omural                   37 mins             █████░░░░░░░░░░░░░░░░░░░░   22.76% 
hudim                    29 mins             ████░░░░░░░░░░░░░░░░░░░░░   18.13% 
rezolusoft.com           8 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   5.46%

💻 Operating System: 
Linux                    2 hrs 43 mins       █████████████████████████   100.0%

```


 Last Updated on 29/10/2024 18:51:42 UTC
<!--END_SECTION:waka-->
