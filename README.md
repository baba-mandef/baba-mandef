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
![Code Time](http://img.shields.io/badge/Code%20Time-963%20hrs%2043%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   12 hrs 18 mins      █████████████░░░░░░░░░░░░   54.79% 
Dart                     9 hrs 23 mins       ██████████░░░░░░░░░░░░░░░   41.81% 
YAML                     29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.19% 
Markdown                 15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.13% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

🔥 Editors: 
VS Code                  21 hrs 58 mins      ████████████████████████░   97.77% 
Android Studio           30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.23%

🐱‍💻 Projects: 
api.ishiro.com           12 hrs 18 mins      █████████████░░░░░░░░░░░░   54.79% 
ishiro                   10 hrs 8 mins       ███████████░░░░░░░░░░░░░░   45.14% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

💻 Operating System: 
Linux                    22 hrs 28 mins      █████████████████████████   100.0%

```


 Last Updated on 29/02/2024 18:38:06 UTC
<!--END_SECTION:waka-->
