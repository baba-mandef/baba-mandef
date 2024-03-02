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
![Code Time](http://img.shields.io/badge/Code%20Time-967%20hrs%202%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     10 hrs 41 mins      █████████████░░░░░░░░░░░░   54.82% 
Python                   8 hrs 2 mins        ██████████░░░░░░░░░░░░░░░   41.26% 
YAML                     29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.52% 
Markdown                 15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.3% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07%

🔥 Editors: 
VS Code                  19 hrs              ████████████████████████░   97.44% 
Android Studio           30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.56%

🐱‍💻 Projects: 
ishiro                   11 hrs 24 mins      ██████████████░░░░░░░░░░░   58.54% 
api.ishiro.com           8 hrs 2 mins        ██████████░░░░░░░░░░░░░░░   41.26% 
flutter                  1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.17% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

💻 Operating System: 
Linux                    19 hrs 30 mins      █████████████████████████   100.0%

```


 Last Updated on 02/03/2024 18:38:02 UTC
<!--END_SECTION:waka-->
