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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C054%20hrs%203%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-273%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               10 hrs 59 mins      ████████████████░░░░░░░░░   64.54% 
CSS                      3 hrs 19 mins       ████░░░░░░░░░░░░░░░░░░░░░   19.48% 
Text                     1 hr 20 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   7.91% 
HTML                     35 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.48% 
SCSS                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.09%

🔥 Editors: 
VS Code                  17 hrs 2 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
kreativ.inc              10 hrs 3 mins       ██████████████░░░░░░░░░░░   59.0% 
etalents.com             6 hrs 46 mins       ██████████░░░░░░░░░░░░░░░   39.78% 
tabler                   12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.22%

💻 Operating System: 
Linux                    17 hrs 2 mins       █████████████████████████   100.0%

```


 Last Updated on 14/05/2024 18:41:07 UTC
<!--END_SECTION:waka-->
