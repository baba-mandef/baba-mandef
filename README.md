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
                       'languages': ['Python', 'Php', 'JS', 'Kotlin'],
                       'tools': ['Django', 'VueJS', 'React', 'Jetpack Compose'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['freelance web and mobile developer', 'Content creator', 'Teacher', 'Mentor'],
            'AskMe': ['DIY', 'Food', 'Africa', 'Science', 'Comics', 'Photography', 'Tech', 'Programming'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-972%20hrs%2048%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     7 hrs 40 mins       ███████████████████████░░   93.17% 
YAML                     33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.81% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02% 
Git Config               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
VS Code                  8 hrs 14 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   7 hrs 29 mins       ██████████████████████░░░   90.87% 
xylophone-flutter        43 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.84% 
flutter                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.29%

💻 Operating System: 
Linux                    8 hrs 14 mins       █████████████████████████   100.0%

```


 Last Updated on 07/03/2024 18:38:56 UTC
<!--END_SECTION:waka-->
