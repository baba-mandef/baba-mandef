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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C071%20hrs%2014%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               2 hrs 34 mins       █████████████░░░░░░░░░░░░   53.98% 
JSON                     42 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.88% 
SCSS                     36 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.77% 
Python                   24 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.71% 
HTML                     14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.05%

🔥 Editors: 
VS Code                  4 hrs 46 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           4 hrs 16 mins       ██████████████████████░░░   89.39% 
api.etalents.com         23 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.33% 
kreativ.inc              4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.6% 
api.korbo.fr             1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.69%

💻 Operating System: 
Linux                    4 hrs 46 mins       █████████████████████████   100.0%

```


 Last Updated on 23/05/2024 18:41:19 UTC
<!--END_SECTION:waka-->
