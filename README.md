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
![Code Time](http://img.shields.io/badge/Code%20Time-967%20hrs%2045%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     10 hrs 30 mins      ███████████████████████░░   93.11% 
YAML                     30 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.55% 
Markdown                 15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.24% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  10 hrs 47 mins      ████████████████████████░   95.64% 
Android Studio           29 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.36%

🐱‍💻 Projects: 
ishiro                   11 hrs 12 mins      ████████████████████████░   99.34% 
xylophone-flutter        2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.37% 
flutter                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.29%

💻 Operating System: 
Linux                    11 hrs 16 mins      █████████████████████████   100.0%

```


 Last Updated on 04/03/2024 18:41:50 UTC
<!--END_SECTION:waka-->
