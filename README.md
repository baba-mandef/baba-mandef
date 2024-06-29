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
                       'languages': ['Python', 'JS', 'Dart'],
                       'tools': ['Django', 'React', 'Flutter'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['Web developer', 'Content Creator', 'Teacher', 'Mentor'],
            'AskMe': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C092%20hrs%2052%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               5 hrs 55 mins       ██████████████████░░░░░░░   74.11% 
HTML                     59 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.5% 
Markdown                 33 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.96% 
CSS                      23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.93% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.78%

🔥 Editors: 
VS Code                  7 hrs 59 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           6 hrs 28 mins       ████████████████████░░░░░   81.02% 
Ustaarabu.org            1 hr 29 mins        ████░░░░░░░░░░░░░░░░░░░░░   18.71% 
kreativ.inc              1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.27%

💻 Operating System: 
Linux                    7 hrs 59 mins       █████████████████████████   100.0%

```


 Last Updated on 29/06/2024 18:40:48 UTC
<!--END_SECTION:waka-->
