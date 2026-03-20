###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'name': 'Abiodoun PARAISO',
            'stack': {
                       'languages': ['Python', 'JS', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'English', 'French'],
                       'tools': ['Django', 'React', 'Flet', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'askme': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'contact': {
                           'Telegram': 'baba_mandef',
                           'Youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-2%2C002%20hrs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20%27Hello%20World%27%20I%27ve%20written-471%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 138 Contributions in the year 2026
 > 
> 📦 178.8 kB Used in GitHub's storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 31 Public repositories 
 > 
> 🔑 6 Private repositories  
 > 
**I'm an early 🐤** 

```text
🌞 Morning    378 commits    ███████░░░░░░░░░░░░░░░░░░   29.19% 
🌆 Daytime    343 commits    ██████░░░░░░░░░░░░░░░░░░░   26.49% 
🌃 Evening    421 commits    ████████░░░░░░░░░░░░░░░░░   32.51% 
🌙 Night      153 commits    ███░░░░░░░░░░░░░░░░░░░░░░   11.81%

```
📅 **I'm most productive on Tuesday** 

```text
Monday       231 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.84% 
Tuesday      280 commits    █████░░░░░░░░░░░░░░░░░░░░   21.62% 
Wednesday    219 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.91% 
Thursday     150 commits    ███░░░░░░░░░░░░░░░░░░░░░░   11.58% 
Friday       167 commits    ███░░░░░░░░░░░░░░░░░░░░░░   12.9% 
Saturday     97 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   7.49% 
Sunday       151 commits    ███░░░░░░░░░░░░░░░░░░░░░░   11.66%

```


```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming languages: 
Other                    6 hrs 59 mins       █████████░░░░░░░░░░░░░░░░   37.02% 
Python                   4 hrs 46 mins       ██████░░░░░░░░░░░░░░░░░░░   25.35% 
HTML                     4 hrs 15 mins       █████░░░░░░░░░░░░░░░░░░░░   22.53% 
Image (svg)              1 hr 18 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.98% 
YAML                     41 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.62%

📝 Editors: 
VS Code                  10 hrs 44 mins      ██████████████░░░░░░░░░░░   56.92% 
Terminal                 5 hrs 23 mins       ███████░░░░░░░░░░░░░░░░░░   28.57% 
Figma                    1 hr 18 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.98% 
GIMP                     47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.19% 
Notion                   27 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.43%

💻 Operating systems: 
Mac                      18 hrs 52 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ███████░░░░░░░░░░░░░░░░░░   29.09% 
CSS                      11 repos            █████░░░░░░░░░░░░░░░░░░░░   20.0% 
JavaScript               7 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.73% 
HTML                     6 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.91% 
PHP                      5 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09%

```



 *Updated on 20/03/2026 09:01:20 UTC*
<!--END_SECTION:waka-->
