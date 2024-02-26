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
![Code Time](http://img.shields.io/badge/Code%20Time-953%20hrs%2038%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   18 hrs 2 mins       ████████████████████████░   97.73% 
Dart                     24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01% 
Markdown                 0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
VS Code                  18 hrs 26 mins      █████████████████████████   99.96% 
Android Studio           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

🐱‍💻 Projects: 
api.ishiro.com           18 hrs 2 mins       ████████████████████████░   97.74% 
ishiro                   24 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

💻 Operating System: 
Linux                    18 hrs 27 mins      █████████████████████████   100.0%

```


 Last Updated on 26/02/2024 18:37:45 UTC
<!--END_SECTION:waka-->
