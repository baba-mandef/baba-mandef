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
![Code Time](http://img.shields.io/badge/Code%20Time-956%20hrs%2042%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   15 hrs 24 mins      █████████████████████░░░░   83.54% 
Dart                     2 hrs 26 mins       ███░░░░░░░░░░░░░░░░░░░░░░   13.27% 
YAML                     18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.72% 
Markdown                 15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.38% 
GitIgnore file           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.08%

🔥 Editors: 
VS Code                  18 hrs              ████████████████████████░   97.6% 
Android Studio           26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.4%

🐱‍💻 Projects: 
api.ishiro.com           15 hrs 24 mins      █████████████████████░░░░   83.54% 
ishiro                   3 hrs 1 min         ████░░░░░░░░░░░░░░░░░░░░░   16.37% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.04%

💻 Operating System: 
Linux                    18 hrs 26 mins      █████████████████████████   100.0%

```


 Last Updated on 27/02/2024 18:39:20 UTC
<!--END_SECTION:waka-->
