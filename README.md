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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C105%20hrs%2055%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
HTML                     1 hr 10 mins        █████████░░░░░░░░░░░░░░░░   36.21% 
Python                   1 hr 6 mins         ████████░░░░░░░░░░░░░░░░░   34.25% 
JavaScript               46 mins             ██████░░░░░░░░░░░░░░░░░░░   24.19% 
Markdown                 6 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   3.5% 
Other                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.17%

🔥 Editors: 
VS Code                  3 hrs 13 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           2 hrs 34 mins       ████████████████████░░░░░   79.58% 
rezolusoft.com.old       24 mins             ███░░░░░░░░░░░░░░░░░░░░░░   12.75% 
Unknown Project          14 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   7.66%

💻 Operating System: 
Linux                    3 hrs 13 mins       █████████████████████████   100.0%

```


 Last Updated on 04/08/2024 18:44:27 UTC
<!--END_SECTION:waka-->
