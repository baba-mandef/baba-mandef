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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C077%20hrs%205%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-418%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               2 hrs 13 mins       ██████████░░░░░░░░░░░░░░░   40.08% 
Python                   2 hrs 10 mins       █████████░░░░░░░░░░░░░░░░   39.27% 
HTML                     37 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.39% 
CSS                      15 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.58% 
Bash                     8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.59%

🔥 Editors: 
VS Code                  5 hrs 32 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
omural                   3 hrs 7 mins        ██████████████░░░░░░░░░░░   56.26% 
api.korbo.fr             2 hrs 17 mins       ██████████░░░░░░░░░░░░░░░   41.38% 
olanike                  4 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.44% 
drf-redesign             2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.61% 
omotunde-mural           0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3%

💻 Operating System: 
Linux                    5 hrs 32 mins       █████████████████████████   100.0%

```


 Last Updated on 12/06/2024 18:43:08 UTC
<!--END_SECTION:waka-->
