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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C211%20hrs%2053%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-424%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      2 hrs 35 mins       ███████████████░░░░░░░░░░   62.91% 
HTML                     57 mins             █████░░░░░░░░░░░░░░░░░░░░   23.13% 
JavaScript               13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.4% 
Python                   8 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.64% 
Text                     7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.07%

🔥 Editors: 
VS Code                  4 hrs 6 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
esmblog                  2 hrs 35 mins       ███████████████░░░░░░░░░░   63.15% 
rezolusoft.com           58 mins             ██████░░░░░░░░░░░░░░░░░░░   23.64% 
ekilibre                 16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.5% 
hudim                    15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.27% 
api.abiodoun.dev         1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44%

💻 Operating System: 
Linux                    4 hrs 6 mins        █████████████████████████   100.0%

```


 Last Updated on 15/11/2024 18:50:21 UTC
<!--END_SECTION:waka-->
