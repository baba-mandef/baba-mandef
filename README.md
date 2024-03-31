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
![Code Time](http://img.shields.io/badge/Code%20Time-996%20hrs%2038%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-270%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     4 hrs 26 mins       ███████████████████████░░   92.0% 
SCSS                     10 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.54% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.66% 
Vue.js                   2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.95% 
HTML                     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.39%

🔥 Editors: 
VS Code                  4 hrs 49 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   4 hrs 27 mins       ███████████████████████░░   92.44% 
henri-front              13 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.49% 
Keystroke                8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.05% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.02%

💻 Operating System: 
Linux                    4 hrs 49 mins       █████████████████████████   100.0%

```


 Last Updated on 31/03/2024 18:38:20 UTC
<!--END_SECTION:waka-->
