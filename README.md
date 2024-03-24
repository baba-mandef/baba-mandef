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
![Code Time](http://img.shields.io/badge/Code%20Time-991%20hrs%2025%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-270%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     15 hrs 13 mins      ████████████████████████░   96.16% 
YAML                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.01% 
Markdown                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.09% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.41% 
Other                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.26%

🔥 Editors: 
VS Code                  15 hrs 50 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   15 hrs 49 mins      █████████████████████████   99.97% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

💻 Operating System: 
Linux                    15 hrs 50 mins      █████████████████████████   100.0%

```


 Last Updated on 24/03/2024 18:39:38 UTC
<!--END_SECTION:waka-->
