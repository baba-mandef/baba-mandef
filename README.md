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
![Code Time](http://img.shields.io/badge/Code%20Time-974%20hrs%2041%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     8 hrs 2 mins        ███████████████████████░░   93.47% 
YAML                     33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.51% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02% 
Git Config               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
VS Code                  8 hrs 36 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   7 hrs 52 mins       ███████████████████████░░   91.53% 
xylophone-flutter        43 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.46% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    8 hrs 36 mins       █████████████████████████   100.0%

```


 Last Updated on 08/03/2024 18:37:55 UTC
<!--END_SECTION:waka-->
