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
                       'languages': ['Python', 'Php', 'JS', 'Kotlin'],
                       'tools': ['Django', 'DRF', 'NuxtJS', 'React', 'Kotlin', 'Electron'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['freelance web and mobile developer', 'Content creator', 'Teacher', 'Mentor'],
            'AskMe': ['DIY', 'Food', 'Africa', 'Science', 'Comics', 'Photography', 'Tech', 'Programming'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-891%20hrs%2047%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 602 Contributions in the Year 2023
 > 
> 📦 98.7 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 42 Public Repositories 
 > 
> 🔑 11 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   1 hr 26 mins        ██████████████████░░░░░░░   74.0% 
Text                     17 mins             ███░░░░░░░░░░░░░░░░░░░░░░   15.03% 
JavaScript               11 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.12% 
HTML                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.65% 
Git                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  1 hr 56 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
lavy                     1 hr 20 mins        █████████████████░░░░░░░░   69.12% 
sub                      36 mins             ███████░░░░░░░░░░░░░░░░░░   30.88%

💻 Operating System: 
Linux                    1 hr 56 mins        █████████████████████████   100.0%

```


 Last Updated on 27/11/2023 18:34:26 UTC
<!--END_SECTION:waka-->
