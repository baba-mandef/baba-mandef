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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C112%20hrs%2024%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     3 hrs 27 mins       █████████████░░░░░░░░░░░░   52.32% 
Python                   2 hrs 4 mins        ███████░░░░░░░░░░░░░░░░░░   31.29% 
JavaScript               41 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.53% 
Markdown                 21 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.53% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.33%

🔥 Editors: 
VS Code                  6 hrs 36 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           6 hrs 6 mins        ███████████████████████░░   92.3% 
rezolusoft.com.old       30 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.7%

💻 Operating System: 
Linux                    6 hrs 36 mins       █████████████████████████   100.0%

```


 Last Updated on 10/08/2024 18:42:20 UTC
<!--END_SECTION:waka-->
