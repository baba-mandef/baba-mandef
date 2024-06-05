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
JavaScript               45 mins             ███████████████████░░░░░░   77.11% 
HTML                     12 mins             █████░░░░░░░░░░░░░░░░░░░░   22.03% 
JSON                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.46% 
CSS                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.25% 
Image (svg)              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.16%

🔥 Editors: 
VS Code                  58 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
omural                   58 mins             █████████████████████████   100.0%

💻 Operating System: 
Linux                    58 mins             █████████████████████████   100.0%

```


 Last Updated on 05/06/2024 18:42:11 UTC
<!--END_SECTION:waka-->
