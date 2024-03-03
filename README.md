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
Dart                     10 hrs 41 mins      ███████████████████░░░░░░   75.77% 
Python                   2 hrs 39 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.87% 
YAML                     29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.49% 
Markdown                 15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.79% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  13 hrs 37 mins      ████████████████████████░   96.51% 
Android Studio           29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.49%

🐱‍💻 Projects: 
ishiro                   11 hrs 24 mins      ████████████████████░░░░░   80.9% 
api.ishiro.com           2 hrs 39 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.87% 
flutter                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.23%

💻 Operating System: 
Linux                    14 hrs 6 mins       █████████████████████████   100.0%

```


 Last Updated on 03/03/2024 18:37:59 UTC
<!--END_SECTION:waka-->
