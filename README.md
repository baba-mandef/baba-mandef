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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C105%20hrs%2032%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               22 mins             ███████████████░░░░░░░░░░   60.42% 
Python                   12 mins             ████████░░░░░░░░░░░░░░░░░   33.52% 
Other                    2 mins              █░░░░░░░░░░░░░░░░░░░░░░░░   6.06%

🔥 Editors: 
VS Code                  37 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
rezolusoft.com           22 mins             ███████████████░░░░░░░░░░   60.42% 
Unknown Project          14 mins             ██████████░░░░░░░░░░░░░░░   39.58%

💻 Operating System: 
Linux                    37 mins             █████████████████████████   100.0%

```


 Last Updated on 03/08/2024 18:42:39 UTC
<!--END_SECTION:waka-->
