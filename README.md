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
![Code Time](http://img.shields.io/badge/Code%20Time-2%2C050%20hrs%2045%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

![Lines of code](https://img.shields.io/badge/From%20%27Hello%20World%27%20I%27ve%20written-471%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 77 Contributions in the year 2026
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
🌞 Morning    269 commits    ██████░░░░░░░░░░░░░░░░░░░   26.42% 
🌆 Daytime    270 commits    ██████░░░░░░░░░░░░░░░░░░░   26.52% 
🌃 Evening    365 commits    █████████░░░░░░░░░░░░░░░░   35.85% 
🌙 Night      114 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   11.2%

```
📅 **I'm most productive on Tuesday** 

```text
Monday       204 commits    █████░░░░░░░░░░░░░░░░░░░░   20.04% 
Tuesday      224 commits    █████░░░░░░░░░░░░░░░░░░░░   22.0% 
Wednesday    177 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.39% 
Thursday     87 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.55% 
Friday       111 commits    ██░░░░░░░░░░░░░░░░░░░░░░░   10.9% 
Saturday     90 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.84% 
Sunday       125 commits    ███░░░░░░░░░░░░░░░░░░░░░░   12.28%

```


```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming languages: 
Other                    9 hrs 30 mins       ████████░░░░░░░░░░░░░░░░░   31.62% 
Image (svg)              9 hrs 16 mins       ███████░░░░░░░░░░░░░░░░░░   30.83% 
Python                   9 hrs 15 mins       ███████░░░░░░░░░░░░░░░░░░   30.79% 
YAML                     41 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.27% 
TOML                     26 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.48%

📝 Editors: 
VS Code                  11 hrs 27 mins      █████████░░░░░░░░░░░░░░░░   38.12% 
Figma                    9 hrs 16 mins       ███████░░░░░░░░░░░░░░░░░░   30.83% 
Terminal                 8 hrs 30 mins       ███████░░░░░░░░░░░░░░░░░░   28.27% 
Notion                   49 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.77%

💻 Operating systems: 
Mac                      30 hrs 4 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   16 repos            ███████░░░░░░░░░░░░░░░░░░   29.09% 
CSS                      11 repos            █████░░░░░░░░░░░░░░░░░░░░   20.0% 
JavaScript               7 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.73% 
HTML                     6 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.91% 
PHP                      5 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09%

```



 *Updated on 24/03/2026 19:42:29 UTC*
<!--END_SECTION:waka-->
