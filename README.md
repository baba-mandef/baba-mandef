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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C242%20hrs%209%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      6 hrs 58 mins       █████████░░░░░░░░░░░░░░░░   36.56% 
HTML                     5 hrs               ██████░░░░░░░░░░░░░░░░░░░   26.21% 
Python                   4 hrs 12 mins       █████░░░░░░░░░░░░░░░░░░░░   22.08% 
Other                    48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.22% 
CSS                      44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.91%

🔥 Editors: 
VS Code                  19 hrs 4 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 10 hrs 48 mins      ██████████████░░░░░░░░░░░   56.63% 
kyff                     5 hrs 37 mins       ███████░░░░░░░░░░░░░░░░░░   29.51% 
tp                       1 hr 17 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.75% 
blog_php                 40 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.5% 
Sharify                  28 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.49%

💻 Operating System: 
Linux                    19 hrs 4 mins       █████████████████████████   100.0%

```


 Last Updated on 26/11/2024 18:49:12 UTC
<!--END_SECTION:waka-->
