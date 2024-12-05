###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'name': 'Abiodoun PARAISO',
            'stack': {
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'askme': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'contact': {
                           'Telegram': 'baba_mandef',
                           'Youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C264%20hrs%2055%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   12 hrs 32 mins      ███████████████░░░░░░░░░░   62.83% 
HTML                     6 hrs               ███████░░░░░░░░░░░░░░░░░░   30.05% 
JavaScript               42 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.55% 
CSS                      31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.63% 
Bash                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.93%

🔥 Editors: 
VS Code                  19 hrs 57 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 19 hrs 57 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    19 hrs 57 mins      █████████████████████████   100.0%

```


 Last Updated on 05/12/2024 18:50:21 UTC
<!--END_SECTION:waka-->
