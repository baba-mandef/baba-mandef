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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C094%20hrs%2028%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               8 hrs 7 mins        ██████████████████░░░░░░░   74.54% 
HTML                     1 hr 17 mins        ███░░░░░░░░░░░░░░░░░░░░░░   11.78% 
Markdown                 53 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.25% 
CSS                      24 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.82% 
JSON                     3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.57%

🔥 Editors: 
VS Code                  10 hrs 53 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           9 hrs 22 mins       █████████████████████░░░░   86.09% 
Ustaarabu.org            1 hr 29 mins        ███░░░░░░░░░░░░░░░░░░░░░░   13.71% 
kreativ.inc              1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.2%

💻 Operating System: 
Linux                    10 hrs 53 mins      █████████████████████████   100.0%

```


 Last Updated on 30/06/2024 18:42:09 UTC
<!--END_SECTION:waka-->
