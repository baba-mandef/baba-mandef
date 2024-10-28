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
HTML                     39 mins             █████████████░░░░░░░░░░░░   54.67% 
Python                   13 mins             ████░░░░░░░░░░░░░░░░░░░░░   19.18% 
Text                     11 mins             ████░░░░░░░░░░░░░░░░░░░░░   16.25% 
CSS                      7 mins              ██░░░░░░░░░░░░░░░░░░░░░░░   9.9%

🔥 Editors: 
VS Code                  1 hr 11 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
omural                   37 mins             █████████████░░░░░░░░░░░░   51.86% 
hudim                    29 mins             ██████████░░░░░░░░░░░░░░░   41.31% 
ekilibre                 4 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.83%

💻 Operating System: 
Linux                    1 hr 11 mins        █████████████████████████   100.0%

```


 Last Updated on 28/10/2024 18:50:15 UTC
<!--END_SECTION:waka-->
