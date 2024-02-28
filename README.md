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
![Code Time](http://img.shields.io/badge/Code%20Time-959%20hrs%2019%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   12 hrs 47 mins      ███████████████░░░░░░░░░░   63.26% 
Dart                     6 hrs 40 mins       ████████░░░░░░░░░░░░░░░░░   33.0% 
YAML                     29 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.4% 
Markdown                 15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.26% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07%

🔥 Editors: 
VS Code                  19 hrs 43 mins      ████████████████████████░   97.53% 
Android Studio           30 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.47%

🐱‍💻 Projects: 
api.ishiro.com           12 hrs 47 mins      ███████████████░░░░░░░░░░   63.26% 
ishiro                   7 hrs 24 mins       █████████░░░░░░░░░░░░░░░░   36.66% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

💻 Operating System: 
Linux                    20 hrs 13 mins      █████████████████████████   100.0%

```


 Last Updated on 28/02/2024 18:38:12 UTC
<!--END_SECTION:waka-->
