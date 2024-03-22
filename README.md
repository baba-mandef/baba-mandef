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
![Code Time](http://img.shields.io/badge/Code%20Time-976%20hrs%2057%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-270%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     5 hrs 26 mins       ██████████████████████░░░   90.77% 
YAML                     16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.69% 
Markdown                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.86% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.09% 
Other                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.59%

🔥 Editors: 
VS Code                  5 hrs 59 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   5 hrs 59 mins       █████████████████████████   99.99% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

💻 Operating System: 
Linux                    5 hrs 59 mins       █████████████████████████   100.0%

```


 Last Updated on 22/03/2024 18:40:22 UTC
<!--END_SECTION:waka-->
