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
                       'languages': ['Python', 'Php', 'JS', 'Dart'],
                       'tools': ['Django', 'Nuxt2', 'React', 'NextJS', 'Flutter'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['freelance web and mobile developer', 'Content creator', 'Teacher', 'Mentor'],
            'AskMe': ['DIY', 'Food', 'Africa', 'Science', 'Comics', 'Photography', 'Tech', 'Programming', 'Mechatronics'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C072%20hrs%2058%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               1 hr 16 mins        ██████████████████░░░░░░░   73.45% 
CSS                      27 mins             ██████░░░░░░░░░░░░░░░░░░░   26.22% 
SCSS                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.34%

🔥 Editors: 
VS Code                  1 hr 43 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           1 hr 43 mins        █████████████████████████   100.0%

💻 Operating System: 
Linux                    1 hr 43 mins        █████████████████████████   100.0%

```


 Last Updated on 29/05/2024 18:41:30 UTC
<!--END_SECTION:waka-->
