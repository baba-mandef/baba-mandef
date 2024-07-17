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
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C102%20hrs%2022%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-420%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
JavaScript               37 mins             ████████████░░░░░░░░░░░░░   49.52% 
HTML                     34 mins             ███████████░░░░░░░░░░░░░░   45.74% 
Python                   1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.65% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.43% 
CSS                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.35%

🔥 Editors: 
VS Code                  1 hr 15 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
omural                   37 mins             ████████████░░░░░░░░░░░░░   50.23% 
omural2                  27 mins             █████████░░░░░░░░░░░░░░░░   36.16% 
rezolusoft.com           8 mins              ███░░░░░░░░░░░░░░░░░░░░░░   11.71% 
api.abiodoun.dev         1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   1.37% 
api.korbo.fr             0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.53%

💻 Operating System: 
Linux                    1 hr 15 mins        █████████████████████████   100.0%

```


 Last Updated on 17/07/2024 18:47:48 UTC
<!--END_SECTION:waka-->
