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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C042%20hrs%2035%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-272%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               9 hrs 15 mins       ███████████████████░░░░░░   79.07% 
CSS                      1 hr 19 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   11.27% 
HTML                     26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.78% 
SCSS                     17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.47% 
JSON                     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.54%

🔥 Editors: 
VS Code                  11 hrs 43 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              9 hrs 59 mins       █████████████████████░░░░   85.26% 
etalents.com             1 hr 38 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.05% 
tabler                   4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.69%

💻 Operating System: 
Linux                    11 hrs 43 mins      █████████████████████████   100.0%

```


 Last Updated on 08/05/2024 18:41:52 UTC
<!--END_SECTION:waka-->
