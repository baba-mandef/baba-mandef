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
![Code Time](http://img.shields.io/badge/Code%20Time-948%20hrs%2014%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-267%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   11 hrs 12 mins      █████████████████████████   99.97% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

🔥 Editors: 
VS Code                  11 hrs 12 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
api.ishiro.com           11 hrs 12 mins      █████████████████████████   100.0%

💻 Operating System: 
Linux                    11 hrs 12 mins      █████████████████████████   100.0%

```


 Last Updated on 23/02/2024 22:24:02 UTC
<!--END_SECTION:waka-->
