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
                           'Telegram': 'ptahemdjehuty',
                           'Mail':'pariso03henri@gmail.com',
                        }
         }
        return Response(ptahemdjehuty, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-728%20hrs%2010%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 447 Contributions in the Year 2023
 > 
> 📦 124.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 44 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   7 hrs 35 mins       ████████████░░░░░░░░░░░░░   48.4% 
JavaScript               6 hrs 57 mins       ███████████░░░░░░░░░░░░░░   44.37% 
Bash                     31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.37% 
HTML                     19 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.11% 
CSS                      7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.83%

🔥 Editors: 
VS Code                  15 hrs 40 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
baba-mandef              6 hrs 3 mins        █████████░░░░░░░░░░░░░░░░   38.59% 
baba-mandef-api          4 hrs 8 mins        ██████░░░░░░░░░░░░░░░░░░░   26.42% 
travel-service-api       3 hrs 49 mins       ██████░░░░░░░░░░░░░░░░░░░   24.43% 
wabo.bj                  1 hr 29 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   9.49% 
quatro                   10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.07%

💻 Operating System: 
Linux                    15 hrs 40 mins      █████████████████████████   100.0%

```


 Last Updated on 06/08/2023 18:34:01 UTC
<!--END_SECTION:waka-->
